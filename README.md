# Gameplay Registry

Gameplay meta definitions for priming.xyz

## Archetypes

### Edit Configuration
-  https://github.com/ParagonsDAO/gameplay-registry/blob/main/game/parallel/archetype.csv

### Trigger Workflow
- https://cloud.temporal.io/namespaces/pacman.kvnrv/schedules/staging_enrich_parallel_deck_archetypes

```
The workflow can be configured with the `edit` function (it retains previous settings)
{
  "period": 30,
  "coverage": 0.6,
  "updateFromRegistry": true
}
```

### Review Metrics
- https://gist.github.com/01-DECOY/93c478d0e4786e324f3b61bec98405e3
