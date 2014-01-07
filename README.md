con_enable 1
engine_no_focus_sleep 0 // you don't lose fps when you alt-tab out
bind "F8" "exec autoexec.cfg" // Strongly recommended to bind: Executes this config again which is needed to have smartcast working every time you start a match.
bind "F11" "toggleconsole"

alias dc disconnect // you can now disconnect by typing "dc" in console, useful for recons and forcing enemy to wait for afk guy

alias rune1 "dota_camera_setpos -2273.898682 1232.745483 982.072876;bind f3 rune2" // Top Rune
alias rune2 "dota_camera_setpos 3035.773438 -2972.680176 966.072937;bind f3 backtome" // Bot Rune
alias backtome "+dota_camera_follow;-dota_camera_follow;+dota_camera_follow;-dota_camera_follow;bind f3 rune1"
bind F3 rune1 // Hit f3 once for top rune, again for bottom, and again to go back to yourself.

dota_force_right_click_attack "1"
dota_screen_shake "0"
dota_player_multipler_orders "1"
dota_player_add_summoned_to_selection "1"
dota_minimap_simple_colors "0"
dota_cheap_water 1
dota_health_hurt_decay_time_max 0  
dota_health_hurt_decay_time_min 0  
dota_health_hurt_delay 0  
dota_health_hurt_threshold 0  
dota_disable_range_finder 0  
dota_minimap_hero_size 800  
dota_minimap_misclick_time 0  

bind "a" "dota_player_units_auto_attack 0;mc_attack" //Attack clicks leave passive stance
bind "h" "dota_player_units_auto_attack 1;dota_stop" //Stop leaves aggressive stance
bind "s" "dota_player_units_auto_attack 0;dota_hold" //Hold leaves passive stance

alias "leftclick" "+sixense_left_click; -sixense_left_click"

alias +info "net_graph 4; +showscores"
alias -info "net_graph 0; -showscores"
bind [l] +info

ragdoll_sleepaftertime "3"
props_break_max_pieces "2"
cl_globallight_shadow_mode 0
cl_particle_fallback_base "4"
cl_particle_fallback_multiplier "0"
cl_detaildist "400"
cl_detailfade "150"
cl_phys_maxticks "3"
cl_interp_ratio 1  
cl_interp 0.035  
r_deferred_height_fog 0
r_deferred_simple_light 1
r_screenspace_aa 0
r_shadow_half_update_rate "1"
r_rainparticledensity "0"
r_flashlightdepthtexture "0"
r_shadowrendertotexture "0"
r_shadowfromworldlights "0"
r_drawmodeldecals "0"
r_decalstaticprops "0"
r_worldlightmin "0.005"
r_worldlights "2"
r_decals "512"
r_decal_overlap_count "1"
r_overlayfademin "1750"
r_overlayfademax "2000"
mp_usehwmvcds "-1"
mp_usehwmmodels "-1"
mat_bumpmap "0"
mat_specular "0"
mat_phong "0"
mat_grain_enable "0"
mat_local_contrast_enable "0"
mat_motion_blur_enabled "0"
mat_picmip "1"
mat_vsync 0
