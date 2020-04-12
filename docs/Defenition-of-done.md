# Definition of Done


When assigned a card or task (story hereafter), there are other requirements that need to be met
beyond having a working code. In the first place, the code must adhere to best
practices as well as coding and testing conventions guidelines of that project.
What follows here are the requirements not captured in the code.

## Documentation

Where applicable, the developer must add the documentation for the added task
to the relevant location. This is specially true in cases of new services, new
features and changes to server configuration. Generally, the code should be self-documenting  
and the comments minimal. Higher level explanations should be placed outside the code.
Finally, the documentation should be targeted to new developers on the team and
minimally technical.

## Verification

The story must be verified by the relevant stakeholders. This may mean getting a sign off
from the product owner, design team or other engineers in cases of technical stories.
All feedback within the scope of the story is the responsibility of the developer,
as well as any other broken functionality in other places in the code. However, if
another feature needs to be updated as a result of these new changes, it must be recorded
as a separate story and may be worked on by any one else.

For example, if your new component breaks the components downstream, you must fix it. However,
if the design team decides that the downstream components must be updated to look differently,
because they no longer carry the feel and look of the app, it is now a separate story.
