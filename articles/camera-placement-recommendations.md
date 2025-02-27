---
author: Athena-Xiao
description: Learn how to place LP cameras for use with Dynamics 365 Connected Spaces Preview, including height, mounting angle, and camera-to-focal-point distance
ms.author: atxiao
ms.date: 10/05/2022
ms.topic: article
title: Camera placement suggestions for Dynamics 365 Connected Spaces Preview
ms.reviewer: v-bholmes
---

# Camera placement suggestions for Dynamics 365 Connected Spaces Preview

> [!NOTE]
> The suggestions in this article are provided for informational purposes only and not for the purpose of providing legal advice. We strongly recommend seeking specialist legal advice when implementing Dynamics 365 Connected Spaces. [See Compliance and responsible use](compliance.md). 

This topic provides camera placement suggestions for Microsoft Dynamics 365 Connected Spaces Preview. It includes general guidelines, and also specific suggestions for height, angle, and camera-to-focal-point-distance to enable the [scenarios and insight goals](camera-placement-general.md).

## General guidelines

Consider the following general guidelines when positioning cameras for Connected Spaces:

- **Lighting height.** Place cameras below lighting fixtures so the fixtures don’t block the cameras.

- **Obstructions.** To avoid obstructing camera views, take note of obstructions such as poles, signage, shelving, walls, and existing 
LP cameras.

- **Environmental backlighting.** Outdoor backlighting affects camera image quality. To avoid severe backlighting conditions, 
avoid directing cameras at external-facing windows and glass doors.

- **Space changes.** Product displays and end caps may get moved after placing cameras. Make sure that camera placement is 
optimized for potential store changes to reduce camera re-positioning.

- **Building structure.** HVAC, sprinklers, and existing wiring may limit hard mounting of cameras.

- **Cable management.** Make sure you can route ethernet cable from planned camera mounting locations to the Power Over Internet 
(PoE) switch.

## Height, focal-point distance, and angle

Consider three things when deciding how to install a camera for Dynamics 365 Connected Spaces:

- Camera height

- Camera-to-focal-point distance 

- The angle of the camera relative to the floor plane

It's also important to know the direction that the majority of people walk (person walking direction) in relation to the camera field of view, or the direction that customers face when standing in line. This direction is important for system performance. 

![Person walking direction.](media/person-walking-direction.PNG "Person walking direction")

The following illustration shows the elevation view for person walking direction. This illustration (and the diagrams below) show a camera’s field of vision relative to the zone (or “sensing area”) from which raw video footage will be used to analyze observational signals, location, and line of business data to produce actionable insights.

![Elevation and plan view.](media/person-walking-direction-2.PNG "Elevation and plan view")

## Camera height

Generally, cameras should be mounted 12-14 feet from the ground. When planning your camera mounting in this range, 
consider obstructions (for example, shelving, hanging lights, hanging signage, and displays) that might affect the 
camera view, and then adjust the height as necessary. 

## Camera-to-focal-point distance

Camera-to-focal-point distance is the linear distance from the focal point (or center focal point of the point of interest) to the 
camera. 

![Camera-to-focal-point-distance.](media/camera-to-focal-point.PNG "Camera-to-focal-point-distance")

This distance is measured on the floor plane.

![How camera-to-focal-point-distance is measured on floor plane.](media/camera-to-focal-point-1.PNG "How camera-to-focal-point-distance is measured on floor plane")

From above, it looks like this:

![How camera-to-focal-point-distance is measured from above.](media/camera-to-focal-point-2.PNG "How camera-to-focal-point-distance is measured from above")

Use the table below to determine the camera’s distance from the focal point based on specific mounting heights. 
These distances are for optimal placement and are suitable for end caps (display effectiveness), queues, or entrances. 
Note that the table provides guidance below the 12-14’ recommendation since some store ceilings are limited in height.

|Camera height|Camera-to-focal-point distance (min/max)|
|-------------|-----------------------------------------|
|8’	|10’-13’|
|10’|7’-13’|
|12’|10’-17’|
|14’|11’-18’|
|16’|12’-22’|
|20’|15’-30’|

The following illustration simulates camera views from the closest and farthest camera-to-focal-point distances.

|Closest| Farthest |
|--------------------------------------------------------|----------------------------------------------------|
|![Closest camera-to-focal-point distance](media/focal-point-closest.PNG "Closest camera-to-focal-point distance")|![Farthest camera-to-focal-point distance](media/focal-point-farthest.PNG "Farthest camera-to-focal-point distance")|

## Camera angle mounting ranges

This section describes acceptable camera angle mounting ranges for store entrances, queues, and end caps. These mounting ranges show 
the acceptable range from optimal placement.

### Store entrances

The following table shows recommendations for store entrances.

|Camera height|Camera-to-focal-point distance|Acceptable camera mounting angle (min/max)|
|--------------|-----------------------------|-----------------------------------------------------------------|
|8’ |9’| +/-40°|
|10’|10’|+/-30°|
|12’|13’|+/-20°|
|16’|18’|+/-10°|
|20’|22’|+/-10°|

The following illustration simulates camera views using the leftmost (-) and rightmost (+) mounting angle recommendations.

|Leftmost view|Rightmost view|
|----------------------------------------------------------|-----------------------------------------------------|
|![Leftmost camera angle](media/camera-angle-left.PNG "Leftmost camera angle")|![Rightmost camera angle](media/camera-angle-right.PNG "Rightmost camera angle")|

The following illustration shows camera placement and mounting angles from above.

![Bird's eye view.](media/camera-angle-top.PNG "Bird's eye view")
 
### End caps

We recommend that you place cameras at 10 feet or more above ground to guarantee the covered area is big enough. Mount end-cap 
cameras in the specified distance from the target within the acceptable 120-degree angle range as shown in the following illustration.

![Acceptable camera angle.](media/camera-angle-acceptable.PNG "Acceptable camera angle")

The following illustration provides simulations for left and right camera views for end caps.

|Left view|Right view|
|----------------------------------------------------------|-----------------------------------------------------|
|![Left view](media/end-cap-left.PNG "Left view")|![Right view](media/end-cap-right.PNG "Right view")|


### Queues

For optimal queue data quality, retractable belt barriers are preferred. 

![Retractable belt queue.](media/retractable-belt-queue.PNG "Retractable belt queue")

This type of barrier is preferred over opaque barriers for queue formation.

#### Zig-zag and linear queues

There are two types of queues: linear and zig-zag.

The following illustration shows recommendations for linear queues:

![Linear queue recommendation.](media/camera-angle-linear-queue.PNG "Linear queue recommendation")
 
The following illustration provides simulations for left and right camera views for linear queues. Note that you can mount the camera 
on the opposite side of the queue. 

|Left view|Right view|
|----------------------------------------------------------|-----------------------------------------------------|
|![Left angle for linear queue](media/camera-angle-linear-left.PNG "Left angle for linear queue")|![Right angle for linear queue](media/camera-angle-linear-right.PNG "Right angle for linear queue")| 

For zip-zag queues, it’s best to avoid placing the camera directly facing the queue line direction, as shown in the 
following illustration. Note that each of the four example camera positions in the illustration provide the ideal view with an 
acceptable deviation of +/- 15 degrees in each direction.

![Camera angle for zig-zag queue.](media/camera-angle-zig-zag-queue.PNG "Camera angle for zig-zag queue")

The following illustrations simulate the view from a camera placed in the ideal locations for a zig-zag queue.

|View 1|View 2|
|----------------------------------------------------------|-----------------------------------------------------|
|![View 1.](media/camera-angle-ideal-zig-zag-1.PNG "View 1")|![View 2](media/camera-angle-ideal-zig-zag-2.PNG "View 2")|

|View 3|View 4|
|----------------------------------------------------------|-----------------------------------------------------|
|![View 3.](media/camera-angle-ideal-zig-zag-3.PNG "View 3")|![View 4](media/camera-angle-ideal-zig-zag-4.PNG "View 4")|
  
#### Fixture (shelving) queues

Fixture queue lines use shelving to guide shoppers and to enable impulse buying. 

![Fixture queues.](media/fixture-queue.PNG "Fixture queues")

This style of queue formation restricts the camera’s view of customers because it blocks customers from the waist down. 
To ensure the highest quality data, mount the cameras to avoid the shelving as much as possible and to capture a complete view of 
customers.

#### Organic queues

Organic queue lines form organically from the point of sale. This style of queue is acceptable if customer queues don’t form 
beyond 2-3 people and the line forms within the zone definition. If the queue length is typically more than 2-3 people, we recommend 
using a retractable belt barrier to help guide the queue direction and ensure the line forms and dwells within the zone definition.

## Placement of in-store cameras and video storage

Images in this guide are intended to represent a potential placement of a customer’s in-store camera(s) by the customer, but camera placement is your responsibility. Once your  cameras are in place, Dynamics 365 Connected Spaces will gather and analyze observational signals, location, and line-of-business data to produce actionable insights. Microsoft does not control or recommend particular placement of in-store cameras ([see Compliance and responsible use](compliance.md)). Connected Spaces stores video footage in Microsoft Dataverse in your Power Platform environment. You can choose not to upload video footage to Microsoft Dataverse by changing your privacy preferences in Settings.

## Next step

After you receive your Azure Stack Edge Pro (2 GPU) device, learn how to [prepare your network and install the device](ase-install.md).
