# RE-UE4SS Cheat List
```
teleport                                                             # Teleport to Cursor Position.
set Character bPressedJump True                                      # Player starts to Jump.
set ISZCharacter health 1000000                                      # Set Player Health to 1000000(Sets everyones health if hosting online).
set ISZCharacter m_Thirst 1000000                                    # Set Player Thirst to 1000000(Sets everyones Thirst if hosting online).
set ISZCharacter m_Hunger 1000000                                    # Set Player Hunger to 1000000(Sets everyones Hunger if hosting online).
set ISZCharacter m_Battery 1000000                                   # Set Player Battery Percent to 1000000(Sets everyones Battery Percent if hosting online).
set ISZCharacter m_BodyTemp 1000000                                  # Set Player Temperature to 1000000(Sets everyones Temperature if hosting online).
set BodyInstanceCore bEnableGravity False                            # Allows Gravity to be Modified.
set WorldSettings GlobalGravityZ 0                                   # Disables your Gravity.
set WorldSettings WorldGravityZ 0                                    # Disables everyones Gravity.
set ISZCharacter m_bBleedingDamage False                             # Stops player from dying to Bleeding.
set ISZCharacter m_bHungerDamage False                               # Stops player from dying to Hunger.
set ISZCharacter m_bThirstDamage False                               # Stops player from dying to Thirst.
set ISZCharacter m_bBodyTempDamage False                             # Stops player from dying to Temperature.
set ISZCharacter bIsDying False                                      # Stops all Status Effects.
set CharacterMovementComponent MaxWalkSpeed 100000                   # Sets Everyone's WalkSpeed to 100000.
set CharacterMovementComponent MaxWalkSpeedCrouched 100000           # Sets Everyone's CrouchSpeed to 100000.
set CharacterMovementComponent WalkableFloorZ -360                   # Everyone Climb Wallks.
set CharacterMovementComponent WalkableFloorAngle -360               # Enables the Above Code.
set CharacterMovementComponent MaxStepHeight 10000                   # Everyone Steps over Everything.
set CharacterMovementComponent GroundFriction 10000000               # Stops everyone from flining off the map (for the most part).
set Actor bHidden True                                               # Everyone goes invisible.
set Actor bCanBeDamaged False                                        # Stops people from being damaged (stops health depleation).
set CharacterMovementComponent MaxAcceleration 10000                 # Everyone Gets up to top speed fast.
set CharacterMovementComponent Buoyancy 10000                        # Floating is more lienient for Everyone.
set CharacterMovementComponent AirControl 10000                      # Basically everyone can now fully fly...
set Actor CustomTimeDilation 2500                                    # The server time goes really really fast.
set Actor bTearOff True                                              # Cloning... Huh.
set GameSession MaxPlayers 999                                       # A Max of 999 people can join you.
set JoinabilitySettings MaxPlayers 999                               # Shows you 999 people can join.
set GameSessionSettings MaxPlayers 999                               # Shows the server list 'X/999' people are in your server.
set ShooterWeapon m_Count 1000000000                                 # Infinite Ammo.
set ShooterWeapon m_Health 1000000000                                # Infinite Gun Durrability.
set ShooterWeapon CurrentAmmoInClip 1000000000                       # No Reload.
set InstantWeaponData HitDamage 1000000000                           # Instakill with any gun (zombies only).
set InstantWeaponData WeaponRange 1000000000                         # Turn any weapon really accurate (needs to be typed everytime you switch weapons).
set WeaponData bCanZoom True                                         # Any gun can scope (needs to be typed everytime you switch weapons).
set ISZVehicle m_Fuel 1000                                           # Infinite Fuel.
set ISZHeli m_EngineParts 1000                                       # No Engine Parts Needed.
DestroyPawns                                                         # Remove & Replace all Vehciles in the World.
```
