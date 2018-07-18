# lumixproto
Lumix GX80 wifi protocol reverse


http://192.168.54.1:60606/A0C9A040EF6D/Server0/ddd

to satisfy camera and finish pairing

 - http://192.168.54.1/cam.cgi?mode=accctrl&type=req_acc&value=4D454930-0100-1000-8001-02FA000430C6&value2=MI%205
 - http://192.168.54.1/cam.cgi?mode=setsetting&type=device_name&value=MI%205

getting some info

- /cam.cgi?mode=getsetting&type=pa
- /cam.cgi?mode=getinfo&type=capability
- /cam.cgi?mode=getinfo&type=allmenu
- /cam.cgi?mode=getinfo&type=curmenu
- /cam.cgi?mode=getinfo&type=lens
- /cam.cgi?mode=getsetting&type=ex_tele_conv
- /cam.cgi?mode=getsetting&type=touch_type
- /cam.cgi?mode=getstate
- /cam.cgi?mode=camcmd&value=playmode

Start video stream
- /cam.cgi?mode=startstream&value=49152
camera starts streaming to client's UDP port 49152 video stream

Change focus (touch screen)

- /cam.cgi?mode=camctrl&type=touch_trace&value=start&value2=264/431
- /cam.cgi?mode=camctrl&type=touch_trace&value=continue&value2=412/469
- /cam.cgi?mode=camctrl&type=touch_trace&value=continue&value2=442/518
- /cam.cgi?mode=camctrl&type=touch_trace&value=stop&value2=502/721

Some other things

- /cam.cgi?mode=camcmd&value=autoreviewunlock
- /cam.cgi?mode=camcmd&value=menu_entry


aperture 2.2

- /cam.cgi?mode=setsetting&type=focal&value=598/256

aperture 1.7

- /cam.cgi?mode=setsetting&type=focal&value=392/256

aperture 22

- /cam.cgi?mode=setsetting&type=focal&value=2304/256

Change gain

- /cam.cgi?mode=setsetting&type=iso&value=auto
- /cam.cgi?mode=setsetting&type=iso&value=400

Change exposure

- /cam.cgi?mode=setsetting&type=exposure&value=0
- /cam.cgi?mode=setsetting&type=exposure&value=-1/3
- /cam.cgi?mode=setsetting&type=exposure&value=5/3
- /cam.cgi?mode=setsetting&type=exposure&value=1
- /cam.cgi?mode=setsetting&type=exposure&value=8/3

Peaking:

- /cam.cgi?mode=setsetting&type=peaking&value=high
- /cam.cgi?mode=setsetting&type=peaking&value=low
- /cam.cgi?mode=setsetting&type=peaking&value=off

Focus assist display
- /cam.cgi?mode=camctrl&type=asst_disp&value=current_auto&value2=mf_asst/0/0
- /cam.cgi?mode=camctrl&type=asst_disp&value=off&value2=mf_asst/0/0
- /cam.cgi?mode=camctrl&type=change_disp_mag&value=560

Focus
- /cam.cgi?mode=camctrl&type=focus&value=wide-normal
- /cam.cgi?mode=camctrl&type=focus&value=wide-fast
- /cam.cgi?mode=camctrl&type=focus&value=tele-normal
- /cam.cgi?mode=camcmd&value=oneshot_af
-

Record
- /cam.cgi?mode=camcmd&value=video_recstart
- /cam.cgi?mode=camcmd&value=video_recstop

Filters
- /cam.cgi?mode=setsetting&type=filter_setting&value=noeffect
- /cam.cgi?mode=setsetting&type=filter_setting&value=pop
- /cam.cgi?mode=setsetting&type=filter_setting&value=retro
- /cam.cgi?mode=setsetting&type=filter_setting&value=old_days

- /cam.cgi?mode=setsetting&type=colormode&value=standard
- /cam.cgi?mode=setsetting&type=colormode&value=vivid
- /cam.cgi?mode=setsetting&type=colormode&value=natural
- /cam.cgi?mode=setsetting&type=colormode&value=bw

Focus mode
- /cam.cgi?mode=setsetting&type=focusmode&value=afs
- /cam.cgi?mode=setsetting&type=focusmode&value=aff
- /cam.cgi?mode=setsetting&type=focusmode&value=afc
- /cam.cgi?mode=setsetting&type=focusmode&value=mf

Metering mode
- /cam.cgi?mode=setsetting&type=lightmetering&value=center
- /cam.cgi?mode=setsetting&type=lightmetering&value=spot
- /cam.cgi?mode=setsetting&type=lightmetering&value=multi

Video format
- /cam.cgi?mode=setsetting&type=videoquality&value=avchd_50p_28mbps
- /cam.cgi?mode=setsetting&type=videoquality&value=mp4_25p_100mbps_4k
- /cam.cgi?mode=setsetting&type=videoquality&value=mp4_24p_100mbps_4k
- /cam.cgi?mode=setsetting&type=videoquality&value=mp4_50p_28mbps
- /cam.cgi?mode=setsetting&type=videoquality&value=mp4_25p_20mbps

