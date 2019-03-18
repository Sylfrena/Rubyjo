- Model, view, controller.
- Traditional approach : Input --> Process --> Output
- MVC approach : `Controller --> Model --> View`
   - Controller : Input logic
   - View : UI
   - Model : Business logic
     ```
      controller --> view
      controller --> model
      view --> model
**Model**
  - implement logic for application's data domain.
  - retrieve and store model state in database.
  - sometimes, in small applications, where the model is more of a conceptual separation instead of a physical one, the dataset takes on the role of a model object.

**Views**
   - displays ui

**Controllers**
   - controller communicates between view and model.

**Pros**

   1. Simultaneous Development
   2. High cohesion
   3. Low coupling among components.
   4. Ease of modification
   5. Multiple views for a model. 

**Cons**
   
   1. Code navigability is more complex due to increased abstraction.
   2. Scattering due to multiple representations ; more difficult to maintain consistency.