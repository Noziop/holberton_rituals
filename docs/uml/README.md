# UML Diagrams Structure

## Core
- [User](core/user.mmd) : Base user management
  - Relations: NotificationPreferences, RitualParticipation, SanctionEngine
- [Notifications](core/notifications.mmd) : Notification system
  - Relations: User, RitualParticipation

## Rituals
- [StandUp](rituals/standup.mmd)
  - Relations: User, RitualParticipation, Metrics
- [SOD](rituals/sod.mmd)
  - Relations: User, RitualParticipation, Metrics
- [PLD](rituals/pld.mmd)
  - Relations: User, RitualParticipation, Metrics

## Participation
- [Participation](participation/participation.mmd)
  - Relations: User, Rituals, Metrics

## Sanctions
- [Sanctions](sanctions/sanctions.mmd)
  - Relations: User, RitualParticipation, Metrics

## Metrics
- [Metrics](metrics/metrics.mmd)
  - Relations: All components