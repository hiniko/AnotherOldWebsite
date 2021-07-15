---
---

[[games]] [[camera]] [[video]] [[Unreal]] [[sim-sickness]]

# 50 Game Camera Mistakes

- [50 Game Camera Mistakes](https://www.youtube.com/watch?v=C7307qRmlMI)

A 2014 GDC talk about lessons learned making the dynamic camera for Journey. All points are listed below.

#todo - Sort these out in to sections

1. Using a dynamic camera when another approach would work. 
 2. Designing levels and camera behaviors that don't match. 
 3. Using global coordinates or quaternions to persist camera state. 
 4. Using a default camera distance that's likely to break line-of-sight. 
 5. Allowing obstacles to break line-of-sight from the side. 
 6. Pushing the camera away from an obstacle while the player is trying to swing the camera towards it. 
 7. Letting the player push the camera inside an obstacle. 
 8. Letting independent forces compete to push the camera. 
 9. Excessively moving the camera to prevent unimportant items from breaking line-of-sight. 
 1.: Letting the camera intersect narrow columns. 
 11. Interpreting a hill as a wall to be avoided. 
 12. Swinging the camera sideways when occluders come from behind. 
 13. Letting the camera's near-clipping-plane intersect the avatar. 
 14. Using the same camera distance for all angles. 
 15. Using the same field-of-view for worm's eye angles and standard angles. 
 16. Shifting pitch, distance, and field-of-view independently. 
 17. Not cutting when the avatar passes through opaque objects.
 18. Letting cuts remap directional controls. 
 19. Breaking the player's sense of direction. 
 20. Violating the 180 degree rule.
 21. Focusing only on the avatar.
 22. Relying on players to control the camera all the time. 
 23. Leaving the camera yaw alone while the player is running. 
 24. Making it hard to judge distances, 
 25. Looking straight ahead as the avatar approaches a cliff. 
 26. Keeping the camera level when the avatar is running on a slope. 
 27. Misusing the "Rule of thirds". 
 28. Using the same logic for ground and air motion. 
 29. Relying entirely on procedural camera behaviors. 
 30. Letting players make themselves lost and confused. 
 31. Rotating excessively to look at nearby targets. 
 32. Translating to look at distance targets. 
 33. Letting the avatar's own body occlude targets ahead. 
 34. Giving the player control over the camera, and then taking it away. 
 35. Immediately applying a camera hint after the player finished turning the camera to look at something. 
 36. Not letting experts explore. 
 37. Not providing inverted controls. 
 38. Responding to accidental controller input. 
 39. Using linear sensitivity. 
 40. Letting the camera pivot drift too far. 
 41.  Using a too small field-of-view. 
 42. Rapidly shifting field-of-view.
 43. Excessively shaking the camera. 
 44. Bouncing the camera with the avatar's walk cycle. 
 45. Translating or rotating up and down when the avatar jumps. 
 46. Rapidly transitioning to a new camera position. 
 47.  Maintaining pitch speed until hitting the pitch limit. 
 48. Developing for the Oculus Rift as the primary camera method. 
 49. Testing with a narrow demographic.
 50. Writing a general "constraint solver" that optimizes for the camera.