# Cycling Mode

**Status:** Public documentation draft

Move+ includes a dedicated Cycling Mode that is currently available for testing and continued development.

The current test version allows users to track a cycling session locally using GPS, view a route and live activity metrics, and review estimated information while riding.

Cycling activity saving, activity history, functional cycling Digital Gear, and real Energy awards are not yet fully released.

## Current testing status

Cycling Mode currently supports:

- Opening the dedicated Cycling tab.
- Requesting the required location permission.
- Starting a local cycling session.
- Displaying the route on a map.
- Showing live cycling metrics.
- Displaying activity-consistency warnings where applicable.
- Stopping the current cycling session.
- Showing an estimated Energy value for testing purposes.

The current version does not yet support:

- Pausing and resuming a dedicated cycling session.
- Saving completed rides.
- Adding rides to normal activity history.
- Adding rides to weekly summaries or achievements.
- Awarding real Energy from the dedicated Cycling Mode.
- Equipping functional cycling Digital Gear.
- Purchasing or claiming cycling gear through the marketplace.

## Starting a cycling session

Before starting a ride, users should:

1. Open the Cycling tab.
2. Enable location services on the device.
3. Grant Move+ the required location permission.
4. Allow the application to obtain a usable GPS signal.
5. Select Start to begin local cycling tracking.

Location quality may vary depending on the device, operating system, buildings, weather, terrain, and surrounding environment.

Cycling Mode is intended for everyday fitness testing. It is not intended to provide medical-grade, survey-grade, competition-grade, or professional cycling measurements.

## During a cycling session

While a cycling session is active, Move+ may display:

- Recorded distance.
- Activity duration.
- Current speed.
- Average speed.
- Maximum speed.
- A visual route on the map.
- GPS or location-signal information.
- Estimated elevation gain.
- Estimated calories.
- An estimated Energy value.

Users can stop the current session from the Cycling screen.

Pause and resume controls are not currently available in the dedicated Cycling Mode.

Leaving the Cycling screen during an active session may require the user to confirm that the ride should be stopped.

## Cycling metrics

The dedicated Cycling Mode may calculate or display the following testing metrics:

### Distance

Distance is calculated from recorded location information during the local session.

### Duration

Duration represents the time recorded while the cycling session is active.

### Speed

Move+ may display current, average, and maximum speed values.

Speed values are calculated from available device and GPS information and should be treated as estimates.

### Route map

The route map provides a visual representation of the recorded cycling session.

The appearance or length of the route displayed on the map should not be treated as an exact professional measurement.

### Calories and elevation

Calories and elevation gain are estimated values based on available activity and location information.

These values are intended for general fitness information and should not be treated as medical or professional measurements.

### GPS signal

The Cycling screen may display information about the current location signal or GPS quality.

Weak or interrupted signals may affect distance, speed, route, and other calculated metrics.

## Activity validation and warnings

Cycling activity data may be checked for consistency while the session is active.

Move+ may display a warning when recorded movement or location information appears incomplete, inconsistent, or unusual.

These warnings are informational during the current testing phase and are intended to help users understand when the recorded activity may be unreliable.

Move+ does not publish its internal validation thresholds, movement filters, warning rules, or abuse-detection methods.

## Energy estimate

The current Cycling Mode may display an estimated Energy value.

This value is a local testing estimate only.

It is not currently:

- Added to the user’s Move+ Energy balance.
- Saved as a completed reward.
- Guaranteed after stopping the ride.
- Convertible into ENR or another asset.
- A representation of monetary value.

Real Cycling Mode Energy eligibility, earning rules, limits, and Digital Gear requirements will be documented under Rewards and Progression when those features are fully released.

## Cycling Digital Gear

The Cycling interface may show early loadout or gear placeholders.

Possible cycling-related categories may include:

- Character.
- Bike.
- Helmet.
- Cycling Shoes.
- Bottle Water.
- Other future cycling equipment.

These interface slots do not currently represent fully released or functional cycling Digital Gear.

Users cannot yet rely on these placeholders for:

- Gear ownership verification.
- Gear equipping.
- Reward multipliers.
- Durability or repair.
- Water depletion or refill.
- Cycling progression.
- Marketplace purchases or claims.

Current Ronin and Base Digital Gear used elsewhere in Move+ should not be assumed to be functional Cycling Mode gear.

Cycling gear utility will be documented separately when the assets and related systems are released.

## Saving and activity history

Dedicated Cycling Mode sessions are not currently saved into the normal Move+ activity history.

Stopping a ride ends the local tracking session, but it does not yet create:

- A saved cycling activity.
- A permanent cycling summary.
- Weekly cycling progress.
- Cycling achievements.
- Personal cycling records.
- Physical shoe mileage updates.
- Community sharing records.

These features remain under development.

## Permissions and platform behavior

Cycling Mode requires location access to record outdoor movement.

Users remain responsible for:

- Granting or denying location permission.
- Starting and stopping each cycling session.
- Reviewing the displayed information.
- Following applicable road and traffic safety rules.
- Using a safe device position while cycling.

Android and iOS may handle location permissions, background activity, battery use, screen behavior, and application suspension differently.

On supported Android devices, Move+ may keep the screen active while a cycling session is running.

Identical screen-wake or uninterrupted background behavior is not currently guaranteed on iOS.

For the most consistent test experience, users should keep Move+ active where practical and follow the permission guidance shown by the application.

## Safety

Users should not operate or interact with the application in a way that distracts them from the road.

A cycling session should be started before riding and stopped only when it is safe to interact with the device.

Move+ does not replace proper cycling equipment, road awareness, navigation tools, or emergency services.

## Current limitations

- Cycling Mode remains under testing.
- Sessions are currently tracked locally.
- Pause and resume are not available.
- Completed rides are not saved.
- Cycling activity history is not available.
- Real Energy is not awarded from dedicated Cycling Mode.
- The displayed Energy value is an estimate only.
- Cycling Digital Gear and loadout slots are placeholders.
- Cycling gear is not currently available through the Move+ Marketplace.
- Metrics may vary depending on the device and GPS environment.
- Platform behavior may differ between Android and iOS.
- Background and off-screen tracking are not guaranteed.

## Related documentation

- Move+ Overview
- Activity Tracking
- Digital Gear
- Rewards and Progression
- Move+ Marketplace
- Privacy Policy
