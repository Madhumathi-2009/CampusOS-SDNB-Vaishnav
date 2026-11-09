# CampusOS

Responsive front-end preview for CampusOS – SDNB Vaishnav College for Women.

## Run

Open `index.html` in a modern browser. There are no package dependencies or build step. Theme, preview profile, and draft notices/assignments/quizzes are stored in that browser's local storage.

## Preview behavior

This starter is a front-end interaction preview. The account form does not authenticate or verify a user; the role switcher is for reviewing role-specific navigation; created records stay in the current browser. The preview deliberately displays empty academic and attendance states instead of inventing college records. It is not suitable for real student information or campus operations.

## Production requirements still to implement

The supplied requirements call for protected Firebase Authentication, institutional identity verification and approvals, Firestore and Storage persistence, server-side authorization and audit trails, and secure Cloud Functions for privileged workflows and AI integration. No Firebase project configuration, institutional identity source, academic rules, approval policy, credit formula, or AI provider configuration was supplied. Those dependencies must be approved and configured before the corresponding production features can be implemented safely. In particular, examination maximums/weights, CR attendance permissions, leaderboard rules and scopes, and the institutional verification/approval process require confirmed policies.
