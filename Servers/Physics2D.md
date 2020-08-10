# Physics2D Server

## C++ Class Hierarchy

- BroadPhase2DSW
  - BroadPhase2DBasic
  - BroadPhase2DHashGrid

- CollisionSolver2DSW

- Object
  - Physics2DDirectBodyState
    - Physics2DDirectBodyStateSW
  - Physics2DDirectSpaceState
    - Physics2DDirectSpaceStateSW
  - Reference
    - Physics2DShapeQueryParameters
    - Physics2DShapeQueryResult
    - Physics2DTestMotionResult
  - Physics2DServer
    - Physics2DServerSW
    - Physics2DServerWrapMT
- Physics2DServerManager

- RID_Data
  - Constraint2DSW
    - AreaPair2DSW
    - Area2Pair2DSW
    - BodyPair2DSW
    - Joint2DSW
      - DampedSpringJoint2DSW
      - GrooveJoint2DSW
      - PinJoint2DSW
  - ShapeOwner2DSW
    - CollisionObject2DSW
      - Area2DSW
      - Body2DSW
  - Shape2DSW
    - CapsuleShape2DSW
    - CircleShape2DSW
    - ConcaveShape2DSW
      - ConcavePolygonShape2DSW
    - ConvexPolygonShape2DSW
    - LineShape2DSW
    - RayShape2DSW
    - RectangleShape2DSW
    - SegmentShape2DSW
  - Space2DSW

  - Step2DSW

## Nodes
