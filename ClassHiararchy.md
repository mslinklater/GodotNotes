# Class Hierarchy

Object
	ARVRPositionalTracker								- A tracked object
	ARVRServer											- Server for AR and VR features
	AudioServer											- Server interface for low level audio access
	CameraServer										- Keeps track of external camera devices
	ClassDB												- Class information repository
	EditorFileSystemDirectory							- A directory for the resource filesystem
	EditorNavigationMeshGenerator
	EditorSelection										- Manages the SceneTree selection in the editor
	EditorVCSInterface									- Version Control System interface which read and writes to the local VCS system in use
	Engine												- Access to the engine properties
	Geometry											- Helper node to calculate generic geometry operations
	GodotSharp
	IP													- Internet Protocol support functions
	Input
	InputMap
	JNISingleton
	JSON
	JSONRPC
	JavaClassWrapper
	JavaScript											- Signleton that connects the engine with the browsers JavaScript context
	MainLoop
		SceneTree
	Marshalls											- Data transformation and encoding helpers
	Node
	OS													- Operating System Functions
	Performance											- Exposes performance related data
	Physics2DDirectBodyState
	Physics2DDirectSpaceState
	Physics2DServer
	PhysicsDirectBodyState
	PhysicsDirectSpaceState
	PhysicsServer
	ProjectSettings										- Contains global variables accessible from everywhere
	Reference											- Base class for reference counted objects
	ResourceLoader
	ResourceSaver
	TranslationServer
	TreeItem
	UndoRedo
	VisualScriptEditor
	VisualServer
	