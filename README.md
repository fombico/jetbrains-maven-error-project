Sample project for https://youtrack.jetbrains.com/issue/IDEA-242002

Comment out the `spring-cloud-starter-contract-verifier` dependency and click to Reload all maven projects.

Observe the error:

```
class org.apache.maven.model.interpolation.StringSearchModelInterpolator cannot be cast to class org.jetbrains.idea.maven.server.embedder.CustomMaven3ModelInterpolator2 (org.apache.maven.model.interpolation.StringSearchModelInterpolator and org.jetbrains.idea.maven.server.embedder.CustomMaven3ModelInterpolator2 are in unnamed module of loader 'app')
```
