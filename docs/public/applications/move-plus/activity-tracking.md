# Activity Tracking

**Status:** Public documentation draft

Move+ provides location-based activity tracking for walking and running. A separate cycling experience is also available for testing and continued development.

Activity tracking is designed for everyday fitness use. It is not intended to provide medical-grade, survey-grade, or professional sports measurements.

## Supported activity modes

### Walking

Walking is a live activity mode in Move+.

Users can record an outdoor walking session, view their route and activity metrics, complete the session, and review the result in their activity summary and history.

### Running

Running uses the same core tracking experience as walking.

Users can record outdoor runs, review route and performance information, and access saved activity summaries and history after completing eligible sessions.

### Cycling

Move+ includes a separate dedicated cycling experience that is currently under testing.

The cycling screen can display locally calculated information such as distance, speed, duration, route, and estimated activity metrics. Saving dedicated cycling activities and awarding Energy from those sessions are not yet fully released.

More information is available in the separate Cycling Mode documentation.

## Starting an activity

Before beginning a walking or running activity, users should:

1. Enable location services on their device.
2. Grant Move+ the required location permission.
3. Select the appropriate activity mode.
4. Allow the application to obtain a usable location signal.
5. Start the activity from the tracking screen.

Location availability and signal quality may be affected by the device, operating system, buildings, weather, and surrounding environment.

## During an activity

While an activity is running, Move+ may display:

- Recorded distance.
- Activity duration.
- Pace or speed information.
- A visual route on the map.
- GPS or location-signal status.
- Estimated calories.
- Estimated elevation gain.
- A preliminary Energy result when the session may be eligible.

Users can pause and resume an active walking or running session from the tracking screen.

Displayed metrics are calculated from available device and location information. Estimated calories, elevation, pace, and similar values should be treated as fitness estimates rather than exact measurements.

## Completing an activity

When a walking or running session is stopped and completed, Move+ may:

- Validate the recorded activity.
- Calculate the final distance and duration.
- Display the completed route.
- Show an activity summary.
- Show an Energy result when the session is eligible.
- Add the completed activity to activity history.
- Update supported progress information such as weekly statistics or personal records.

Some progress features may vary by platform, application version, and account eligibility.

## Activity validation

Move+ checks activity information for consistency before rewards are finalized.

Validation may consider the quality and continuity of recorded movement and location data. Activities that contain invalid, incomplete, or suspicious information may be rejected, recorded without rewards, or produce a reduced eligible result.

Move+ does not publish its internal validation thresholds, security rules, or abuse-detection methods.

## Energy eligibility

Tracking an activity does not guarantee an Energy reward.

Energy eligibility may depend on:

- The activity being successfully completed and validated.
- The user’s current account eligibility.
- An active iOS subscription.
- Compatible linked Digital Gear.
- Active reward rules and application configuration.
- Any applicable activity requirements or daily limits.

Subscription access is currently available on iOS. Android does not currently offer a subscription.

Android users can still use supported activity-tracking features. Linked Digital Gear and other active eligibility rules may separately affect whether an activity qualifies for Energy.

Exact earning rates, limits, multipliers, and progression rules are maintained in the separate Rewards and Progression documentation.

Energy does not represent guaranteed monetary value or a guaranteed right to token conversion or cash withdrawal.

## Activity summaries and progress

Move+ includes activity and progress views that may provide:

- A summary after completing an activity.
- Saved walking and running activity history.
- Weekly activity summaries.
- Personal running records.
- Profile and achievement progress.
- Physical shoe mileage tracking on supported platforms and activity flows.

The dedicated cycling experience does not yet save completed rides into the normal activity history.

## Maps and location

Move+ uses map and location services to display the user’s activity route and calculate movement-related information.

A visible route is a representation of the recorded session. Reward calculations and activity validation are not based only on the appearance or length of the route displayed on the map.

Move+ may also use optional device fitness-platform information to improve parts of the activity experience. On supported Android devices, this may include Health Connect data. Location-based tracking remains necessary for supported outdoor activity and reward validation.

## Background and off-screen behavior

Tracking behavior can vary between Android and iOS because each platform manages location permissions, background activity, battery use, and application suspension differently.

Android includes support for active-session location handling when the required permissions are granted. Move+ does not currently promise identical uninterrupted off-screen tracking behavior on iOS.

For the most consistent recording experience, users should follow the in-app permission guidance and keep Move+ active where practical during an activity.

## Privacy and user control

Move+ only begins recording an activity after the user starts a session.

Users remain responsible for:

- Granting or denying device permissions.
- Starting, pausing, resuming, and stopping an activity.
- Reviewing the recorded activity before relying on its results.
- Following the applicable privacy and permission information presented by the application.

Detailed information about location data, fitness data, storage, and user rights belongs in the Move+ Privacy Policy.

## Current limitations

- Dedicated Cycling Mode remains under testing.
- Dedicated cycling activity saving and Energy rewards are not yet fully released.
- Location accuracy varies by device and environment.
- Estimated fitness metrics are not medical or professional measurements.
- Energy rewards depend on validation and eligibility.
- Some progress and fitness-platform features may differ between Android and iOS.
- Background and off-screen behavior may differ between platforms.

## Related documentation

- Move+ Overview
- Cycling Mode
- Digital Gear
- Rewards and Progression
- Move+ Marketplace
- Privacy Policy
