Hi 

Please use the command mvn clean install to execute the project. 

The project has auotmated code to launch swaglabs android app and login to application.

Bugs identified in the app:

Issue1: In Empty cart screen we are showing Qty, Description labels which aren't required.

Reproducible steps:

1. Launch the app and login with standarduser
2. Tap on Empty cart
3. Observe that on top of screen we can see Qty, Description labels and aren't required when user hasn't added any product

Expected: Qty, Description labels should be hidden in empty cart screen.

Issue2: Able to tap on Checkout screen in Empty cart

1. Launch the app and login with standarduser
2. Tap on Empty cart
3. We can see Checkout, Continue Shopping lable
4. Tap on Checkout
5. User navigated to personal details screen.

Expected: Checkout CTA on empty cart screen isn't requirred.
