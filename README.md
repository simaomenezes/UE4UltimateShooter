# UE4UltimateSShooter
Programar Games com C++ e a Unreal Engine

#OBS: 
- The Branch :
	2 - Module Project Setup
		Branch:	CameraSpringArm
		Branch:	FollowCamera
  		Branch:	ControllersAndInput
  		Branch:	AddingAMesh
  		Branch:	RotateCharacterToMovement
  	3 - Module Animations
  		Branch:	RunAnimations
		Branch:	TrimmingAnimations	
  		This Branch Have implemented animations and base weapon mechanics-> WeaponMechanics


# Exemple of logs
	UE_LOG(LogTemp, Warning, TEXT("BeginPlay() called!"));

	int myInt{ 45 };
	UE_LOG(LogTemp, Warning, TEXT("int myInt: %d"), myInt);

	float myFloat{ 3.55664f };
	UE_LOG(LogTemp, Warning, TEXT("float myFloat: %f"), myFloat);

	double myDouble{ 0.522222 };
	UE_LOG(LogTemp, Warning, TEXT("double myDouble: %lf"), myDouble);

	char myChar{ 'J'};
	UE_LOG(LogTemp, Warning, TEXT("char myChar: %c"), myChar);

	wchar_t wideChar{ L'J'};
	UE_LOG(LogTemp, Warning, TEXT("wchar_t wideChar: %lc"), wideChar);

	bool myBool{ true };
	UE_LOG(LogTemp, Warning, TEXT("bool myBool: %d"), myBool);

	UE_LOG(LogTemp, Warning, TEXT("int: %d, float: %f, bool: %d"), myInt, myFloat, myBool);

	FString myString{ TEXT("My String!!!!") };
	UE_LOG(LogTemp, Warning, TEXT("FString myString: %s"), *myString);

	UE_LOG(LogTemp, Warning, TEXT("Name of instance: %s"), *GetName());
