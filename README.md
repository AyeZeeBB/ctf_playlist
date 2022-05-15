# ctf checksum: -1302836445
# ctf_playlist

```
		custom_ctf
		{
			inherit defaults
			vars
			{
				//ui_slot                                      regular_2
				image                                          worlds_edge
				video                                          worlds_edge
				panel_image                                    panel_worlds_edge
				visible                                        1
				battlechatter_enabled                          1
				name                                           custom_ctf
				description                                    "Two teams each have their own color flag placed in their home base. The objective is to steal the other team's flag and take it to their own base"
				abbreviation                                   "Capture The Flag"
				lobbytitle                                     "Capture The Flag"

				pin_match_type                                 survival
				enable_nessies                                 0
				max_teams                                      2
				max_players                                    18
				min_players                                    1

				// General Settings:
				survival_shields                               1
				skydive_ziplines_enabled                       0
				survival_infinite_ammo                         1
				survival_custom_deploy                         1
				ground_loot_enable                             0
				lootbin_loot_enable                            0
				waiting_for_players_has_black_screen           0
				waiting_for_players_countdown_seconds          0
				survival_commentary_kill_leader_enabled        0
				survival_commentary_first_blood_enabled        0
				bloodhound_bird_cluster                        0

				// Intro Settings:
				character_select_time_min                      0
				character_select_time_max                      0
				charselect_picking_delay_after_all             0
				survival_enable_squad_intro                    0
				survival_enable_gladiator_intros               0

				jump_from_plane_enabled                        0
				match_ending_enabled                           0
				sur_circle_start_paused                        1

				// CTF Settings:
				//// General CTF Settings:
				survival_jumpkit_enabled                       1    //Enables double jump
				survival_wallrun_enabled                       1    //Enables wallrun
				default_shield_hp                              75   //Sets Sheilds
				give_ult_after_capture                         1    //Fills up ult after capture
				use_legend_abilitys                            0    //Uses Legends defualt abilitys instead of classes
				respawn_timer                                  10   //Amount of seconds it takes to repsawn
				take_weapons_from_flag_carrier                 0    //Takes weapons from flag carrier and gives a dataknife that does 75 damage
				give_flag_carrier_speed_boost                  0    //Gives the flag carrier a speed boost when holding the flag

				////CTF Score And Round time:
				max_score				                       5    //Set max amount of flag captures
				round_time				                       1500 //Sets time limit for rounds

				////Respawn Classes: Uses the exact same format as custom_tdm
				//Class 1
				ctf_respawn_class1_name                        "Close-Quarters"
				ctf_respawn_class1_primary                     "mp_weapon_r97 optic_cq_hcog_classic barrel_stabilizer_l4_flash_hider stock_tactical_l3 bullets_mag_l3"
				ctf_respawn_class1_secondary                   "mp_weapon_autopistol optic_cq_hcog_classic barrel_stabilizer_l4_flash_hider bullets_mag_l3"
				ctf_respawn_class1_tactical                    "mp_ability_area_sonar_scan"
				ctf_respawn_class1_ultimate                    "mp_weapon_jump_pad"
				//Class 2
				ctf_respawn_class2_name                        "Heavy"
				ctf_respawn_class2_primary                     "mp_weapon_lmg optic_cq_hcog_classic barrel_stabilizer_l4_flash_hider stock_tactical_l3 highcal_mag_l3"
				ctf_respawn_class2_secondary                   "mp_weapon_energy_shotgun shotgun_bolt_l3"
				ctf_respawn_class2_tactical                    "mp_weapon_bubble_bunker"
				ctf_respawn_class2_ultimate                    "mp_weapon_grenade_gas"
				//Class 3
				ctf_respawn_class3_name                        "Assault"
				ctf_respawn_class3_primary                     "mp_weapon_vinson optic_cq_hcog_classic stock_tactical_l3 highcal_mag_l3"
				ctf_respawn_class3_secondary                   "mp_weapon_wingman optic_cq_hcog_classic highcal_mag_l3"
				ctf_respawn_class3_tactical                    "mp_ability_area_sonar_scan"
				ctf_respawn_class3_ultimate                    "mp_weapon_jump_pad"
				//Class 4
				ctf_respawn_class4_name                        "Marksman"
				ctf_respawn_class4_primary                     "mp_weapon_g2 optic_ranged_aog_variable barrel_stabilizer_l4_flash_hider stock_sniper_l3 bullets_mag_l3"
				ctf_respawn_class4_secondary                   "mp_weapon_alternator_smg optic_cq_hcog_classic bullets_mag_l3 barrel_stabilizer_l4_flash_hider stock_tactical_l3"
				ctf_respawn_class4_tactical                    "mp_weapon_dirty_bomb"
				ctf_respawn_class4_ultimate                    "mp_weapon_grenade_defensive_bombardment"
				//Class 5
				ctf_respawn_class5_name                        "Sniper"
				ctf_respawn_class5_primary                     "mp_weapon_doubletake optic_ranged_aog_variable stock_sniper_l3 energy_mag_l3"
				ctf_respawn_class5_secondary                   "mp_weapon_shotgun optic_cq_hcog_classic shotgun_bolt_l3"
				ctf_respawn_class5_tactical                    "mp_ability_grapple"
				ctf_respawn_class5_ultimate                    "mp_weapon_jump_pad"
				//End of CTF Settings
			}
			gamemodes { custom_ctf { maps {
				mp_rr_canyonlands_64k_x_64k                    1
				mp_rr_canyonlands_mu1                          1
				mp_rr_desertlands_64k_x_64k                    1
				mp_rr_desertlands_64k_x_64k_nx                 1
				mp_rr_canyonlands_mu1_night                    1
				mp_rr_canyonlands_staging                      1
				mp_rr_aqueduct								   1
			} } }
		}
```
