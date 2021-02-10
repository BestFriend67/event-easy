# src

- [app/](./src/app)
  - [api/](./src/app/api)
    - [categoryOptions.js](./src/app/api/categoryOptions.js)
    - [mockApi.js](./src/app/api/mockApi.js)
    - [sampleData.js](./src/app/api/sampleData.js)
  - [common/](./src/app/common)
    - [errors/](./src/app/common/errors)
      - [ErrorComponent.jsx](./src/app/common/errors/ErrorComponent.jsx)
    - [form/](./src/app/common/form)
      - [MyDateInput.jsx](./src/app/common/form/MyDateInput.jsx)
      - [MySelectInput.jsx](./src/app/common/form/MySelectInput.jsx)
      - [MyTextArea.jsx](./src/app/common/form/MyTextArea.jsx)
      - [MyTextInput.jsx](./src/app/common/form/MyTextInput.jsx)
    - [modals/](./src/app/common/modals)
      - [ModalManager.jsx](./src/app/common/modals/ModalManager.jsx)
      - [ModalWrapper.jsx](./src/app/common/modals/ModalWrapper.jsx)
    - [util/](./src/app/common/util)
      - [util.js](./src/app/common/util/util.js)
  - [config/](./src/app/config)
    - [firebase.js](./src/app/config/firebase.js)
  - [firestore/](./src/app/firestore)
    - [firebaseService.js](./src/app/firestore/firebaseService.js)
    - [firestoreService.js](./src/app/firestore/firestoreService.js)
  - [hooks/](./src/app/hooks)
    - [useFirestoreCollection.js](./src/app/hooks/useFirestoreCollection.js)
    - [useFirestoreDoc.js](./src/app/hooks/useFirestoreDoc.js)
  - [layout/](./src/app/layout)
    - [App.jsx](./src/app/layout/App.jsx)
    - [LoadingComponent.jsx](./src/app/layout/LoadingComponent.jsx)
    - [ScrollToTop.jsx](./src/app/layout/ScrollToTop.jsx)
    - [styles.css](./src/app/layout/styles.css)
- [features/](./src/features)
  - [auth/](./src/features/auth)
    - [AccountPage.jsx](./src/features/auth/AccountPage.jsx)
    - [LoginInForm.jsx](./src/features/auth/LoginInForm.jsx)
    - [RegisterForm.jsx](./src/features/auth/RegisterForm.jsx)
    - [SocialLogin.jsx](./src/features/auth/SocialLogin.jsx)
  - [events/](./src/features/events)
    - [eventDashboard/](./src/features/events/eventDashboard)
      - [EventDashboard.jsx](./src/features/events/eventDashboard/EventDashboard.jsx)
      - [EventFilters.jsx](./src/features/events/eventDashboard/EventFilters.jsx)
      - [EventList.jsx](./src/features/events/eventDashboard/EventList.jsx)
      - [EventListAttendee.jsx](./src/features/events/eventDashboard/EventListAttendee.jsx)
      - [EventListItem.jsx](./src/features/events/eventDashboard/EventListItem.jsx)
      - [EventListItemPlaceholder.jsx](./src/features/events/eventDashboard/EventListItemPlaceholder.jsx)
    - [eventDetailed/](./src/features/events/eventDetailed)
      - [EventDetailedChat.jsx](./src/features/events/eventDetailed/EventDetailedChat.jsx)
      - [EventDetailedHeader.jsx](./src/features/events/eventDetailed/EventDetailedHeader.jsx)
      - [EventDetailedInfo.jsx](./src/features/events/eventDetailed/EventDetailedInfo.jsx)
      - [EventDetailedPage.jsx](./src/features/events/eventDetailed/EventDetailedPage.jsx)
      - [EventDetailedSidebar.jsx](./src/features/events/eventDetailed/EventDetailedSidebar.jsx)
    - [eventForm/](./src/features/events/eventForm)
      - [EventForm.jsx](./src/features/events/eventForm/EventForm.jsx)
  - [home/](./src/features/home)
    - [HomePage.jsx](./src/features/home/HomePage.jsx)
  - [nav/](./src/features/nav)
    - [NavBar.jsx](./src/features/nav/NavBar.jsx)
    - [SignedIn.jsx](./src/features/nav/SignedIn.jsx)
    - [SignedOut.jsx](./src/features/nav/SignedOut.jsx)
  - [sandbox/](./src/features/sandbox)
    - [Sandbox.js](./src/features/sandbox/Sandbox.js)
    - [TestModal.jsx](./src/features/sandbox/TestModal.jsx)
    - [testReducer.js](./src/features/sandbox/testReducer.js)
  - [store/](./src/features/store)
    - [actions/](./src/features/store/actions)
      - [actionTypes.js](./src/features/store/actions/actionTypes.js)
      - [authActions.js](./src/features/store/actions/authActions.js)
      - [eventActions.js](./src/features/store/actions/eventActions.js)
    - [reducers/](./src/features/store/reducers)
      - [asyncReducer.js](./src/features/store/reducers/asyncReducer.js)
      - [authReducer.js](./src/features/store/reducers/authReducer.js)
      - [eventReducer.js](./src/features/store/reducers/eventReducer.js)
      - [modalReducer.js](./src/features/store/reducers/modalReducer.js)
      - [rootReducer.js](./src/features/store/reducers/rootReducer.js)
    - [configStore.js](./src/features/store/configStore.js)
- [index.js](./src/index.js)
- [reportWebVitals.js](./src/reportWebVitals.js)
- [setupTests.js](./src/setupTests.js)