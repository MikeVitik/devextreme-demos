Our **Diagram** widget allows you to restrict edit operations as needed. To prohibit a specific operation, set its corresponding option within the [editing](/Documentation/ApiReference/UI_Widgets/dxDiagram/Configuration/editing/) property to **false**.

In this demo, the [onRequestEditOperation](Documentation/ApiReference/UI_Widgets/dxDiagram/Configuration/#onRequestEditOperation) function implements complex logic to determine whether an operation is allowed. The **updateUI** event parameter indicates whether the event is raised by a user action or via a UI update. If a user tries to perform a prohibited action, an error message is displayed.