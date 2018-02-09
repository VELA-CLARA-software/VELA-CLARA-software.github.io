Welcome to TimDocTest’s documentation![¶](#welcome-to-timdoctest-s-documentation "Permalink to this headline")
==============================================================================================================

Contents:

VELA\_CLARA\_Camera\_Screens[¶](#module-VELA_CLARA_Screen_Control "Permalink to this headline")
===============================================================================================

 *class*`VELA_CLARA_Screen_Control.`{.descclassname}`screenController`{.descname}[¶](#VELA_CLARA_Screen_Control.screenController "Permalink to this definition")
:   screenController Doc String

     `debugMessagesOff`{.descname}(*(screenController)arg1*) → None[¶](#VELA_CLARA_Screen_Control.screenController.debugMessagesOff "Permalink to this definition")
    :   

     `debugMessagesOn`{.descname}(*(screenController)arg1*) → None[¶](#VELA_CLARA_Screen_Control.screenController.debugMessagesOn "Permalink to this definition")
    :   

     `getACTPOS`{.descname}(*(screenController)arg1*, *(str)arg2*) → float :[¶](#VELA_CLARA_Screen_Control.screenController.getACTPOS "Permalink to this definition")
    :   Returns the current actuator position.

     `getILockStates`{.descname}(*(screenController)arg1*, *(str)arg2*) → object[¶](#VELA_CLARA_Screen_Control.screenController.getILockStates "Permalink to this definition")
    :   

     `getScreenObject`{.descname}(*(screenController)arg1*, *(str)arg2*) → screenObject :[¶](#VELA_CLARA_Screen_Control.screenController.getScreenObject "Permalink to this definition")
    :   Returns the screen object (name).

     `getScreenState`{.descname}(*(screenController)arg1*, *(str)arg2*) → str :[¶](#VELA_CLARA_Screen_Control.screenController.getScreenState "Permalink to this definition")
    :   Returns the current SCREEN\_STATE.

     `isHElement`{.descname}(*(screenController)arg1*, *(str)arg2*, *(SCREEN\_STATE)arg3*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.isHElement "Permalink to this definition")
    :   Returns true if the element SCREEN\_STATE state is a horizontal
        device.

     `isHEnabled`{.descname}(*(screenController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.isHEnabled "Permalink to this definition")
    :   Returns true if the horizontal stage is enabled.

     `isHIn`{.descname}(*(screenController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.isHIn "Permalink to this definition")
    :   Returns true if the horizontal stage is out.

     `isHOut`{.descname}(*(screenController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.isHOut "Permalink to this definition")
    :   Returns true if the horizontal stage is out.

     `isScreenIn`{.descname}(*(screenController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.isScreenIn "Permalink to this definition")
    :   Returns true if any of the screen devices are inserted.

     `isScreenInState`{.descname}(*(screenController)arg1*, *(str)arg2*, *(SCREEN\_STATE)arg3*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.isScreenInState "Permalink to this definition")
    :   Returns true if screen is currently in SCREEN\_STATE state.

     `isVElement`{.descname}(*(screenController)arg1*, *(str)arg2*, *(SCREEN\_STATE)arg3*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.isVElement "Permalink to this definition")
    :   Returns true if the element SCREEN\_STATE state is a vertical
        device.

     `isVEnabled`{.descname}(*(screenController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.isVEnabled "Permalink to this definition")
    :   Returns true if the vertical stage is enabled.

     `isVIn`{.descname}(*(screenController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.isVIn "Permalink to this definition")
    :   Returns true if the vertical stage is in.

     `isVOut`{.descname}(*(screenController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.isVOut "Permalink to this definition")
    :   Returns true if the vertical stage is out.

     `isYAGIn`{.descname}(*(screenController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.isYAGIn "Permalink to this definition")
    :   Returns true if the YAG screen is in.

     `is_HandV_OUT`{.descname}(*(screenController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.is_HandV_OUT "Permalink to this definition")
    :   Returns true if both stages are out.

     `jogScreen`{.descname}(*(screenController)arg1*, *(str)arg2*, *(float)arg3*) → None :[¶](#VELA_CLARA_Screen_Control.screenController.jogScreen "Permalink to this definition")
    :   Jogs the screen from its current position by jog (mm) - for
        expert use and calibration.

     `messagesOff`{.descname}(*(screenController)arg1*) → None[¶](#VELA_CLARA_Screen_Control.screenController.messagesOff "Permalink to this definition")
    :   

     `messagesOn`{.descname}(*(screenController)arg1*) → None[¶](#VELA_CLARA_Screen_Control.screenController.messagesOn "Permalink to this definition")
    :   

     `moveScreenTo`{.descname}(*(screenController)arg1*, *(str)arg2*, *(SCREEN\_STATE)arg3*) → None :[¶](#VELA_CLARA_Screen_Control.screenController.moveScreenTo "Permalink to this definition")
    :   Will move the screen (name) to SCREEN\_STATE state if it exists
        (as defined in the config file).

     `resetPosition`{.descname}(*(screenController)arg1*, *(str)arg2*) → None :[¶](#VELA_CLARA_Screen_Control.screenController.resetPosition "Permalink to this definition")
    :   Resets the device to the position defined by SDEV.

     `setEX`{.descname}(*(screenController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.setEX "Permalink to this definition")
    :   Sets the screen in motion after setPosition is called.

     `setPosition`{.descname}(*(screenController)arg1*, *(str)arg2*, *(float)arg3*) → None :[¶](#VELA_CLARA_Screen_Control.screenController.setPosition "Permalink to this definition")
    :   Sets the target position of the screen (mm) - for expert use and
        calibration.

     `setScreenSDEV`{.descname}(*(screenController)arg1*, *(str)arg2*, *(SCREEN\_STATE)arg3*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.setScreenSDEV "Permalink to this definition")
    :   Set screen device - the first part of moving a screen. Set the
        device to SCREEN\_STATE state.

     `setScreenTrigger`{.descname}(*(screenController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Screen_Control.screenController.setScreenTrigger "Permalink to this definition")
    :   Set screen trigger == 1 - the second part of moving a screen.
        This will set the stage in motion.

     `silence`{.descname}(*(screenController)arg1*) → None[¶](#VELA_CLARA_Screen_Control.screenController.silence "Permalink to this definition")
    :   

     `verbose`{.descname}(*(screenController)arg1*) → None[¶](#VELA_CLARA_Screen_Control.screenController.verbose "Permalink to this definition")
    :   

 *class*`VELA_CLARA_Screen_Control.`{.descclassname}`screenObject`{.descname}[¶](#VELA_CLARA_Screen_Control.screenObject "Permalink to this definition")
:   This struct contains the screen object - inc. type of screen (HV
    mover, pneumatic etc.), and horizontal and vertical state. It also
    gives the names of all the devices (positions) for a given screen.

VELA\_CLARA\_Camera\_IA[¶](#module-VELA_CLARA_Camera_IA_Control "Permalink to this headline")
=============================================================================================

 *class*`VELA_CLARA_Camera_IA_Control.`{.descclassname}`ACQUIRE_STATE`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.ACQUIRE_STATE "Permalink to this definition")
:   Enum to interpet the acquistion state of camera.

 *class*`VELA_CLARA_Camera_IA_Control.`{.descclassname}`CAM_STATE`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.CAM_STATE "Permalink to this definition")
:   Enum to interpet the power state of camera.

 *class*`VELA_CLARA_Camera_IA_Control.`{.descclassname}`CAPTURE_STATE`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.CAPTURE_STATE "Permalink to this definition")
:   Enum to interpet the capturing state of camera.

 *class*`VELA_CLARA_Camera_IA_Control.`{.descclassname}`WRITE_CHECK`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.WRITE_CHECK "Permalink to this definition")
:   Enum to interpet the saving errors of camera.

 *class*`VELA_CLARA_Camera_IA_Control.`{.descclassname}`WRITE_STATE`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.WRITE_STATE "Permalink to this definition")
:   Enum to interpet the saving state of camera.

 *class*`VELA_CLARA_Camera_IA_Control.`{.descclassname}`cameraIAController`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController "Permalink to this definition")
:   cameraIAController Doc String

     `getCamIAObjConstRef`{.descname}(*(cameraIAController)arg1*, *(str)name*) → cameraObject :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.getCamIAObjConstRef "Permalink to this definition")
    :   Returns a reference to camera ‘name’.

     `getOfflineIARef`{.descname}(*(cameraIAController)arg1*) → offlineImageAnalyser :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.getOfflineIARef "Permalink to this definition")
    :   This is a ref to the class that holds the functions for offline
        image analysis.

     `getSelectedIARef`{.descname}(*(cameraIAController)arg1*) → cameraObject :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.getSelectedIARef "Permalink to this definition")
    :   Returns a reference to selected camera.

     `getVCIARef`{.descname}(*(cameraIAController)arg1*) → cameraObject :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.getVCIARef "Permalink to this definition")
    :   Returns a reference to VC camera.

     `get_CA_PEND_IO_TIMEOUT`{.descname}(*(cameraIAController)arg1*) → float[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.get_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `isAcquiring`{.descname}(*(cameraIAController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.isAcquiring "Permalink to this definition")
    :   Returns True if camera ‘name’ is acquiring.

     `isNotAcquiring`{.descname}(*(cameraIAController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.isNotAcquiring "Permalink to this definition")
    :   Returns True if camera ‘name’ is not acquiring.

     `isOFF`{.descname}(*(cameraIAController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.isOFF "Permalink to this definition")
    :   Returns True if camera ‘name’ is OFF.

     `isON`{.descname}(*(cameraIAController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.isON "Permalink to this definition")
    :   Returns True if camera ‘name’ is ON.

     `selectedCamera`{.descname}(*(cameraIAController)arg1*) → str :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.selectedCamera "Permalink to this definition")
    :   Returns the name (string) of the current selected camera.

     `setCamera`{.descname}(*(cameraIAController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.setCamera "Permalink to this definition")
    :   Returns True if camera ‘name’ is set as selected camera.

     `set_CA_PEND_IO_TIMEOUT`{.descname}(*(cameraIAController)arg1*, *(float)arg2*) → None[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.set_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `startAcquiring`{.descname}(*(cameraIAController)arg1*) → bool :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.startAcquiring "Permalink to this definition")
    :   Sets Selected camera acquiring and returns True if successful.

     `startVCAcquiring`{.descname}(*(cameraIAController)arg1*) → bool :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.startVCAcquiring "Permalink to this definition")
    :   Sets VC Camera acquiring and returns True if successful.

     `stopAcquiring`{.descname}(*(cameraIAController)arg1*) → bool :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.stopAcquiring "Permalink to this definition")
    :   Stops Selected camera acquiring and returns True if succesful.

     `stopVCAcquiring`{.descname}(*(cameraIAController)arg1*) → bool :[¶](#VELA_CLARA_Camera_IA_Control.cameraIAController.stopVCAcquiring "Permalink to this definition")
    :   Stops VC Camera acquiring and returns True if successful.

 *class*`VELA_CLARA_Camera_IA_Control.`{.descclassname}`cameraIAObject`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject "Permalink to this definition")
:   cameraIAObject Doc String

     `bitDepth`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.bitDepth "Permalink to this definition")
    :   Bit depth of image.

     `covXY`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.covXY "Permalink to this definition")
    :   Covariance of beam in millemetres squared.

     `imageHeight`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.imageHeight "Permalink to this definition")
    :   Vertical length of full image in pixels.

     `imageWidth`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.imageWidth "Permalink to this definition")
    :   Horizontal length of full image in pixels.

     `pix2mm`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.pix2mm "Permalink to this definition")
    :   Conversion factor for convert pixel value to mm. (mm =
        pix2mm\*pix)

     `sigmaX`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.sigmaX "Permalink to this definition")
    :   Horizontal sigma of beam in millemetres.

     `sigmaY`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.sigmaY "Permalink to this definition")
    :   Vertical sigma of beam in millemetres.

     `x`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.x "Permalink to this definition")
    :   Horizontal position of beam’s centroid in millemetres.

     `xCenterPix`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.xCenterPix "Permalink to this definition")
    :   Horizontal calibrated center of pipe (0 of ideal trajectory) in
        pixels.

     `xPix`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.xPix "Permalink to this definition")
    :   Horizontal position of beam’s centroid in pixels.

     `xRad`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.xRad "Permalink to this definition")
    :   Horizontal radius of mask used in image analysis in pixels.

     `xSigmaPix`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.xSigmaPix "Permalink to this definition")
    :   Horizontal sigma of beam in pixels.

     `xyCovPix`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.xyCovPix "Permalink to this definition")
    :   Covariance of beam in pixels squared.

     `y`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.y "Permalink to this definition")
    :   Vertical position of beam’s centroid in millemetres.

     `yCenterPix`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.yCenterPix "Permalink to this definition")
    :   Vertical calibrated center of pipe (0 of ideal trajectory) in
        pixels.

     `yPix`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.yPix "Permalink to this definition")
    :   Vertical position of beam’s centroid in pixels.

     `yRad`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.yRad "Permalink to this definition")
    :   Vertical radius of mask used in image analysis in pixels.

     `ySigmaPix`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraIAObject.ySigmaPix "Permalink to this definition")
    :   Vertical sigma of beam in pixels.

 *class*`VELA_CLARA_Camera_IA_Control.`{.descclassname}`cameraObject`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraObject "Permalink to this definition")
:   cameraObject Doc String

     `IA`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraObject.IA "Permalink to this definition")
    :   Object (cameraIAObject) containing all the Image Anaylsis data.

     `acquireState`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraObject.acquireState "Permalink to this definition")
    :   Horizontal position of beam’s centroid in millemetres.

     `name`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraObject.name "Permalink to this definition")
    :   Name of the camera (defined in the config file).

     `pvRoot`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraObject.pvRoot "Permalink to this definition")
    :   Camera’s PV preffix (defined in the config file).

     `screenName`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraObject.screenName "Permalink to this definition")
    :   Name of screen associated Camera (defined in config file).

     `state`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraObject.state "Permalink to this definition")
    :   The state indicating whether Camera is ‘reachable’, i.e. power
        is on.

 *class*`VELA_CLARA_Camera_IA_Control.`{.descclassname}`cameraOfflineIAObject`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject "Permalink to this definition")
:   cameraOfflineIAObject Doc String

     `DirectCutLevelES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.DirectCutLevelES "Permalink to this definition")
    :   1

     `RRThresholdES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.RRThresholdES "Permalink to this definition")
    :   1

     `bkgrndName`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.bkgrndName "Permalink to this definition")
    :   1

     `cxyBVN`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.cxyBVN "Permalink to this definition")
    :   8

     `cxyMLE`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.cxyMLE "Permalink to this definition")
    :   1

     `dataSize`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.dataSize "Permalink to this definition")
    :   5

     `filterES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.filterES "Permalink to this definition")
    :   1

     `imageHeight`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.imageHeight "Permalink to this definition")
    :   6

     `imageName`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.imageName "Permalink to this definition")
    :   1

     `imageWidth`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.imageWidth "Permalink to this definition")
    :   7

     `manualCropH`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.manualCropH "Permalink to this definition")
    :   1

     `manualCropW`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.manualCropW "Permalink to this definition")
    :   1

     `manualCropX`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.manualCropX "Permalink to this definition")
    :   1

     `manualCropY`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.manualCropY "Permalink to this definition")
    :   1

     `maskRXES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.maskRXES "Permalink to this definition")
    :   1

     `maskRYES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.maskRYES "Permalink to this definition")
    :   1

     `maskXES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.maskXES "Permalink to this definition")
    :   1

     `maskXProjection`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.maskXProjection "Permalink to this definition")
    :   3

     `maskYES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.maskYES "Permalink to this definition")
    :   1

     `maskYProjection`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.maskYProjection "Permalink to this definition")
    :   4

     `pixToMmES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.pixToMmES "Permalink to this definition")
    :   1

     `rawData`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.rawData "Permalink to this definition")
    :   1

     `rotation`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.rotation "Permalink to this definition")
    :   8

     `savedCroppedX`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.savedCroppedX "Permalink to this definition")
    :   1

     `savedCroppedY`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.savedCroppedY "Permalink to this definition")
    :   1

     `sigmaCutES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.sigmaCutES "Permalink to this definition")
    :   1

     `sxBVN`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.sxBVN "Permalink to this definition")
    :   7

     `sxMLE`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.sxMLE "Permalink to this definition")
    :   1

     `syBVN`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.syBVN "Permalink to this definition")
    :   7

     `syMLE`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.syMLE "Permalink to this definition")
    :   1

     `totalPixelIntensity`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.totalPixelIntensity "Permalink to this definition")
    :   1

     `useBVN`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.useBVN "Permalink to this definition")
    :   1

     `useBkgrnd`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.useBkgrnd "Permalink to this definition")
    :   1

     `useDirectCutLevelFromES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.useDirectCutLevelFromES "Permalink to this definition")
    :   1

     `useFilterFromES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.useFilterFromES "Permalink to this definition")
    :   1

     `useManualCrop`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.useManualCrop "Permalink to this definition")
    :   1

     `useMaskFromES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.useMaskFromES "Permalink to this definition")
    :   1

     `usePixToMmFromES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.usePixToMmFromES "Permalink to this definition")
    :   1

     `useRRThresholdFromES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.useRRThresholdFromES "Permalink to this definition")
    :   1

     `useSigmaCutFromES`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.useSigmaCutFromES "Permalink to this definition")
    :   1

     `x0`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.x0 "Permalink to this definition")
    :   9

     `xBVN`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.xBVN "Permalink to this definition")
    :   5

     `xMLE`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.xMLE "Permalink to this definition")
    :   9

     `xProjection`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.xProjection "Permalink to this definition")
    :   1

     `xRad`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.xRad "Permalink to this definition")
    :   2

     `y0`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.y0 "Permalink to this definition")
    :   1

     `yBVN`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.yBVN "Permalink to this definition")
    :   6

     `yMLE`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.yMLE "Permalink to this definition")
    :   2

     `yProjection`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.yProjection "Permalink to this definition")
    :   2

     `yRad`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.cameraOfflineIAObject.yRad "Permalink to this definition")
    :   4

 *class*`VELA_CLARA_Camera_IA_Control.`{.descclassname}`controller`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.controller "Permalink to this definition")
:   controller Doc String

     `getILockStates`{.descname}(*(controller)arg1*, *(str)arg2*) → object[¶](#VELA_CLARA_Camera_IA_Control.controller.getILockStates "Permalink to this definition")
    :   getILockStates( (controller)arg1, (str)arg2) -\> None

     `getILockStatesStr`{.descname}(*(controller)arg1*, *(str)arg2*) → object[¶](#VELA_CLARA_Camera_IA_Control.controller.getILockStatesStr "Permalink to this definition")
    :   getILockStatesStr( (controller)arg1, (str)arg2) -\> None

     `get_CA_PEND_IO_TIMEOUT`{.descname}(*(controller)arg1*) → float[¶](#VELA_CLARA_Camera_IA_Control.controller.get_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   get\_CA\_PEND\_IO\_TIMEOUT( (controller)arg1) -\> None

     `set_CA_PEND_IO_TIMEOUT`{.descname}(*(controller)arg1*, *(float)arg2*) → None[¶](#VELA_CLARA_Camera_IA_Control.controller.set_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   set\_CA\_PEND\_IO\_TIMEOUT( (controller)arg1, (float)arg2) -\>
        None

 *class*`VELA_CLARA_Camera_IA_Control.`{.descclassname}`offlineImageAnalyser`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser "Permalink to this definition")
:   offlineImageAnalyser Doc String

     `CoIA`{.descname}[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.CoIA "Permalink to this definition")
    :   Object (cameraOffline IMage Object) containing all the offline
        Image Anaylsis data.

     `analyse`{.descname}(*(offlineImageAnalyser)arg1*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.analyse "Permalink to this definition")
    :   Based of your set up this will analyse your image and output the
        resulst to to object CoIA

     `isAnalysing`{.descname}(*(offlineImageAnalyser)arg1*) → bool :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.isAnalysing "Permalink to this definition")
    :   return true if analysis if running in a thread.

     `loadBackgroundImage`{.descname}(*(offlineImageAnalyser)arg1*, *(std\_vector\_double)arg2*, *(str)data*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.loadBackgroundImage "Permalink to this definition")
    :   Takes in 1D array, raw background image data.

     `loadImage`{.descname}(*(offlineImageAnalyser)arg1*, *(std\_vector\_double)arg2*, *(str)data*, *(int)height*, *(int)width*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.loadImage "Permalink to this definition")
    :   Takes in 1D array, raw image data.

     `setESDirectCut`{.descname}(*(offlineImageAnalyser)arg1*, *(float)double*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.setESDirectCut "Permalink to this definition")
    :   Set Direct Cut.

     `setESFilter`{.descname}(*(offlineImageAnalyser)arg1*, *(int)int*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.setESFilter "Permalink to this definition")
    :   Set Filter.

     `setESMask`{.descname}(*(offlineImageAnalyser)arg1*, *(int)x*, *(int)y*, *(int)rx*, *(int)ry*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.setESMask "Permalink to this definition")
    :   Set Mask parameterss

     `setESPixToMm`{.descname}(*(offlineImageAnalyser)arg1*, *(float)double*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.setESPixToMm "Permalink to this definition")
    :   Set pixel to mm ratio

     `setESRRThreshold`{.descname}(*(offlineImageAnalyser)arg1*, *(float)double*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.setESRRThreshold "Permalink to this definition")
    :   Set R-squared threshold.

     `setESSigmaCut`{.descname}(*(offlineImageAnalyser)arg1*, *(float)double*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.setESSigmaCut "Permalink to this definition")
    :   Set Sigma Cut.

     `setManualCrop`{.descname}(*(offlineImageAnalyser)arg1*, *(int)x*, *(int)y*, *(int)w*, *(int)h*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.setManualCrop "Permalink to this definition")
    :   Manual crop sett parameters

     `useBackground`{.descname}(*(offlineImageAnalyser)arg1*, *(bool)bool*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.useBackground "Permalink to this definition")
    :   Set a bool to determine whether or not to use background.

     `useESDirectCut`{.descname}(*(offlineImageAnalyser)arg1*, *(bool)bool*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.useESDirectCut "Permalink to this definition")
    :   Set a bool to determine whether or not to use Expert Setting
        Direct Cut.

     `useESFilter`{.descname}(*(offlineImageAnalyser)arg1*, *(bool)bool*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.useESFilter "Permalink to this definition")
    :   Set a bool to determine whether or not to use Expert Setting
        Filter.

     `useESMask`{.descname}(*(offlineImageAnalyser)arg1*, *(bool)bool*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.useESMask "Permalink to this definition")
    :   Set a bool to determine whether or not to use Expert Setting
        Mask.

     `useESPixToMm`{.descname}(*(offlineImageAnalyser)arg1*, *(bool)bool*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.useESPixToMm "Permalink to this definition")
    :   Set a bool to determine whether or not to use Expert Setting
        pixel to mm ratio.

     `useESRRThreshold`{.descname}(*(offlineImageAnalyser)arg1*, *(bool)bool*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.useESRRThreshold "Permalink to this definition")
    :   Set a bool to determine whether or not to use Expert Setting
        R-squared threshold.

     `useESSigmaCut`{.descname}(*(offlineImageAnalyser)arg1*, *(bool)bool*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.useESSigmaCut "Permalink to this definition")
    :   Set a bool to determine whether or not to use Expert Setting
        Sigma Cut.

     `useManualCrop`{.descname}(*(offlineImageAnalyser)arg1*, *(bool)bool*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.useManualCrop "Permalink to this definition")
    :   Set a bool to determine whether or not to use Manual Crop.

     `writeData`{.descname}(*(offlineImageAnalyser)arg1*, *(str)arg2*) → None :[¶](#VELA_CLARA_Camera_IA_Control.offlineImageAnalyser.writeData "Permalink to this definition")
    :   Writes data into a csv file.

VELA\_CLARA\_Camera\_DAQ[¶](#module-VELA_CLARA_Camera_DAQ_Control "Permalink to this headline")
===============================================================================================

 *class*`VELA_CLARA_Camera_DAQ_Control.`{.descclassname}`ACQUIRE_STATE`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.ACQUIRE_STATE "Permalink to this definition")
:   Enum to interpet the acquistion state of camera.

 *class*`VELA_CLARA_Camera_DAQ_Control.`{.descclassname}`CAM_STATE`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.CAM_STATE "Permalink to this definition")
:   Enum to interpet the power state of camera.

 *class*`VELA_CLARA_Camera_DAQ_Control.`{.descclassname}`CAPTURE_STATE`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.CAPTURE_STATE "Permalink to this definition")
:   Enum to interpet the capturing state of camera.

 *class*`VELA_CLARA_Camera_DAQ_Control.`{.descclassname}`WRITE_CHECK`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.WRITE_CHECK "Permalink to this definition")
:   Enum to interpet the saving errors of camera.

 *class*`VELA_CLARA_Camera_DAQ_Control.`{.descclassname}`WRITE_STATE`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.WRITE_STATE "Permalink to this definition")
:   Enum to interpet the saving state of camera.

 *class*`VELA_CLARA_Camera_DAQ_Control.`{.descclassname}`cameraDAQController`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController "Permalink to this definition")
:    `collectAndSave`{.descname}(*(cameraDAQController)arg1*, *(int)Number of Shots*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.collectAndSave "Permalink to this definition")
    :   Collects and saves images from selected camera in a thread

     `collectAndSaveVC`{.descname}(*(cameraDAQController)arg1*, *(int)Number of Shots*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.collectAndSaveVC "Permalink to this definition")
    :   Collects and saves images from VC camera in a thread

     `getCamDAQObjConstRef`{.descname}(*(cameraDAQController)arg1*, *(str)name*) → cameraObject :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.getCamDAQObjConstRef "Permalink to this definition")
    :   Returns a reference to camera ‘name’

     `getCameraNames`{.descname}(*(cameraDAQController)arg1*) → std\_vector\_string :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.getCameraNames "Permalink to this definition")
    :   Returns a list of all the camera names.

     `getSelectedDAQRef`{.descname}(*(cameraDAQController)arg1*) → cameraObject :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.getSelectedDAQRef "Permalink to this definition")
    :   Returns a reference to selected camera

     `getVCDAQRef`{.descname}(*(cameraDAQController)arg1*) → cameraObject :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.getVCDAQRef "Permalink to this definition")
    :   Returns a reference to VC camera

     `get_CA_PEND_IO_TIMEOUT`{.descname}(*(cameraDAQController)arg1*) → float[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.get_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `getlatestDirectory`{.descname}(*(cameraDAQController)arg1*) → str :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.getlatestDirectory "Permalink to this definition")
    :   Returns a string indicating directory selected camers last saved
        images to.

     `isAcquiring`{.descname}(*(cameraDAQController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.isAcquiring "Permalink to this definition")
    :   Returns True if camera ‘name’ is acquiring

     `isNotAcquiring`{.descname}(*(cameraDAQController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.isNotAcquiring "Permalink to this definition")
    :   Returns True if camera ‘name’ is not acquiring

     `isOFF`{.descname}(*(cameraDAQController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.isOFF "Permalink to this definition")
    :   Returns True if camera ‘name’ is OFF

     `isON`{.descname}(*(cameraDAQController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.isON "Permalink to this definition")
    :   Returns True if camera ‘name’ is ON

     `killCollectAndSave`{.descname}(*(cameraDAQController)arg1*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.killCollectAndSave "Permalink to this definition")
    :   Returns True if stopped the selected camera collectAndSave
        process

     `killCollectAndSaveVC`{.descname}(*(cameraDAQController)arg1*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.killCollectAndSaveVC "Permalink to this definition")
    :   Returns True if stopped the VC camera collectAndSave process

     `selectedCamera`{.descname}(*(cameraDAQController)arg1*) → str :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.selectedCamera "Permalink to this definition")
    :   Returns the name (string) of the current selected camera

     `setCamera`{.descname}(*(cameraDAQController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.setCamera "Permalink to this definition")
    :   Returns True if camera ‘name’ is set as selected camera

     `set_CA_PEND_IO_TIMEOUT`{.descname}(*(cameraDAQController)arg1*, *(float)arg2*) → None[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.set_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `startAcquiring`{.descname}(*(cameraDAQController)arg1*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.startAcquiring "Permalink to this definition")
    :   Sets Selected camera acquiring and returns True if successful

     `startVCAcquiring`{.descname}(*(cameraDAQController)arg1*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.startVCAcquiring "Permalink to this definition")
    :   Sets VC Camera acquiring and returns True if successful

     `stopAcquiring`{.descname}(*(cameraDAQController)arg1*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.stopAcquiring "Permalink to this definition")
    :   Stops Selected camera acquiring and returns True if succesful

     `stopVCAcquiring`{.descname}(*(cameraDAQController)arg1*) → bool :[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQController.stopVCAcquiring "Permalink to this definition")
    :   Stops VC Camera acquiring and returns True if successful

 *class*`VELA_CLARA_Camera_DAQ_Control.`{.descclassname}`cameraDAQObject`{.descname}(*read only values*)[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject "Permalink to this definition")
:    `acquisitionPeriod`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.acquisitionPeriod "Permalink to this definition")
    :   Time (seconds) of full acquisition period, that includes
        expoture time.

     `captureState`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.captureState "Permalink to this definition")
    :   The state indicating whether the Camera is collecting images.

     `exposureTime`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.exposureTime "Permalink to this definition")
    :   Time (seconds) of exposure for single camera image.

     `frequency`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.frequency "Permalink to this definition")
    :   Frequency of Camera’s image acquisiton.

     `latestDirectory`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.latestDirectory "Permalink to this definition")
    :   Latest directory images were saved to.

     `maxShots`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.maxShots "Permalink to this definition")
    :   The maximum number of shots that can be taken in one burst.

     `numberOfShots`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.numberOfShots "Permalink to this definition")
    :   The number of shots set to collect.

     `sensorTemp`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.sensorTemp "Permalink to this definition")
    :   Temperature of Sensor (CCD) in celcius.

     `shotsTaken`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.shotsTaken "Permalink to this definition")
    :   The number of shots taken and collected.

     `writeCheck`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.writeCheck "Permalink to this definition")
    :   A check to indicated the ability to save images (good/error).

     `writeErrorMessage`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.writeErrorMessage "Permalink to this definition")
    :   If there is an error with saving the images a message will be
        displayed here.

     `writeState`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraDAQObject.writeState "Permalink to this definition")
    :   The state indicating whether the Camera is saving images

 *class*`VELA_CLARA_Camera_DAQ_Control.`{.descclassname}`cameraObject`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraObject "Permalink to this definition")
:   cameraObject Doc String

     `DAQ`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraObject.DAQ "Permalink to this definition")
    :   Object (cameraDAQObject) containing all the DAQ data.

     `acquireState`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraObject.acquireState "Permalink to this definition")
    :   Horizontal position of beam’s centroid in millemetres.

     `name`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraObject.name "Permalink to this definition")
    :   Name of the camera (defined in the config file).

     `pvRoot`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraObject.pvRoot "Permalink to this definition")
    :   Camera’s PV preffix (defined in the config file).

     `screenName`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraObject.screenName "Permalink to this definition")
    :   Name of screen associated Camera (defined in config file).

     `state`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraObject.state "Permalink to this definition")
    :   The state indicating whether Camera is ‘reachable’, i.e. power
        is on.

     `streamingIPAddress`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.cameraObject.streamingIPAddress "Permalink to this definition")
    :   IP address for the camera live stream.

 *class*`VELA_CLARA_Camera_DAQ_Control.`{.descclassname}`controller`{.descname}[¶](#VELA_CLARA_Camera_DAQ_Control.controller "Permalink to this definition")
:   controller Doc String

     `getILockStates`{.descname}(*(controller)arg1*, *(str)arg2*) → object[¶](#VELA_CLARA_Camera_DAQ_Control.controller.getILockStates "Permalink to this definition")
    :   getILockStates( (controller)arg1, (str)arg2) -\> None

     `getILockStatesStr`{.descname}(*(controller)arg1*, *(str)arg2*) → object[¶](#VELA_CLARA_Camera_DAQ_Control.controller.getILockStatesStr "Permalink to this definition")
    :   getILockStatesStr( (controller)arg1, (str)arg2) -\> None

     `get_CA_PEND_IO_TIMEOUT`{.descname}(*(controller)arg1*) → float[¶](#VELA_CLARA_Camera_DAQ_Control.controller.get_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   get\_CA\_PEND\_IO\_TIMEOUT( (controller)arg1) -\> None

     `set_CA_PEND_IO_TIMEOUT`{.descname}(*(controller)arg1*, *(float)arg2*) → None[¶](#VELA_CLARA_Camera_DAQ_Control.controller.set_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   set\_CA\_PEND\_IO\_TIMEOUT( (controller)arg1, (float)arg2) -\>
        None

VELA\_CLARA\_LLRF[¶](#module-VELA_CLARA_LLRF_Control "Permalink to this headline")
==================================================================================

 *class*`VELA_CLARA_LLRF_Control.`{.descclassname}`liberaLLRFController`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController "Permalink to this definition")
:   liberaLLRFController Doc String: Main functions for LLRF control

     `RFOutput`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.RFOutput "Permalink to this definition")
    :   Return true if RF output is enabled.

     `clearMask`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.clearMask "Permalink to this definition")
    :   Clear the masks for trace ‘name’

     `clearRollingAverage`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.clearRollingAverage "Permalink to this definition")
    :   Clear the Rolling Average data for trace ‘name’ This also rests
        other counters to zero, meaning any/all current data in the
        rolling averages will be lost.

     `elapsedTime`{.descname}(*(liberaLLRFController)arg1*) → long :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.elapsedTime "Permalink to this definition")
    :   ms since the last startTimer call, (if negative then no call to
        startTimerhas been made)

     `fullCavityTraceName`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → str :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.fullCavityTraceName "Permalink to this definition")
    :   Returns trace name being used

     `getActivePulseCount`{.descname}(*(liberaLLRFController)arg1*) → int :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getActivePulseCount "Permalink to this definition")
    :   Return number of pulses with amplitude \> 0 sinze connection

     `getAmpCalibration`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getAmpCalibration "Permalink to this definition")
    :   Return Linear Conversion of Amplitude from LLRF units to MV/m

     `getAmpFF`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getAmpFF "Permalink to this definition")
    :   Return Amplitude(FF) in LLRF Units

     `getAmpLLRF`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getAmpLLRF "Permalink to this definition")
    :   Return Amplitude in LLRF Units

     `getAmpMVM`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getAmpMVM "Permalink to this definition")
    :   Return Amplitude in MV/m

     `getAmpSP`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getAmpSP "Permalink to this definition")
    :   Return Amplitude(SP) in LLRF Units

     `getAverageTraceData`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getAverageTraceData "Permalink to this definition")
    :   Return latest average trace data for Channel ‘name’

     `getBreakDownRate`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getBreakDownRate "Permalink to this definition")
    :   Return estimate of breakdowns per second.

     `getCavFwdPhase`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavFwdPhase "Permalink to this definition")
    :   Return latest cavity forward phase trace

     `getCavFwdPhaseAv`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavFwdPhaseAv "Permalink to this definition")
    :   Return latest cavity forward phase average trace

     `getCavFwdPhaseBuffer`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavFwdPhaseBuffer "Permalink to this definition")
    :   Return buffer of cavity forward phase rf\_trace objects

     `getCavFwdPhaseData`{.descname}(*(liberaLLRFController)arg1*) → rf\_trace :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavFwdPhaseData "Permalink to this definition")
    :   Return latest cavity forward phase rf\_trace object

     `getCavFwdPower`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavFwdPower "Permalink to this definition")
    :   Return latest cavity forward power trace

     `getCavFwdPowerAv`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavFwdPowerAv "Permalink to this definition")
    :   Return latest cavity forward power average trace

     `getCavFwdPowerBuffer`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavFwdPowerBuffer "Permalink to this definition")
    :   Return buffer of cavity forward power rf\_trace objects

     `getCavFwdPowerData`{.descname}(*(liberaLLRFController)arg1*) → rf\_trace :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavFwdPowerData "Permalink to this definition")
    :   Return latest cavity forward power rf\_trace object

     `getCavRevPhase`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavRevPhase "Permalink to this definition")
    :   Return latest cavity reverse phase trace

     `getCavRevPhaseAv`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavRevPhaseAv "Permalink to this definition")
    :   Return latest cavity reverse phase average trace

     `getCavRevPhaseBuffer`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavRevPhaseBuffer "Permalink to this definition")
    :   Return buffer of cavity reverse phase rf\_trace objects

     `getCavRevPhaseData`{.descname}(*(liberaLLRFController)arg1*) → rf\_trace :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavRevPhaseData "Permalink to this definition")
    :   Return latest cavity reverse phase rf\_trace object

     `getCavRevPower`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavRevPower "Permalink to this definition")
    :   Return latest cavity reverse power trace

     `getCavRevPowerAv`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavRevPowerAv "Permalink to this definition")
    :   Return latest cavity reverse power average trace

     `getCavRevPowerBuffer`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavRevPowerBuffer "Permalink to this definition")
    :   Return buffer of cavity reverse power rf\_trace objects

     `getCavRevPowerData`{.descname}(*(liberaLLRFController)arg1*) → rf\_trace :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCavRevPowerData "Permalink to this definition")
    :   Return latest cavity reverse power rf\_trace object

     `getChannelNames`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getChannelNames "Permalink to this definition")
    :   Return Channel names (defined in config file)

     `getCrestPhiLLRF`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getCrestPhiLLRF "Permalink to this definition")
    :   Return the Crest Phase in LLRF Units

     `getHiMask`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getHiMask "Permalink to this definition")
    :   Get High mask for trace ‘name’

     `getILockStates`{.descname}(*(liberaLLRFController)arg1*, *(str)arg2*) → object[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getILockStates "Permalink to this definition")
    :   

     `getKlyFwdPhase`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyFwdPhase "Permalink to this definition")
    :   Return latest klystron forward phase trace

     `getKlyFwdPhaseBuffer`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyFwdPhaseBuffer "Permalink to this definition")
    :   Return buffer of klystron forward phase rf\_trace objects

     `getKlyFwdPhaseData`{.descname}(*(liberaLLRFController)arg1*) → rf\_trace :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyFwdPhaseData "Permalink to this definition")
    :   Return latest klystron forward phase rf\_trace object

     `getKlyFwdPower`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyFwdPower "Permalink to this definition")
    :   Return latest klystron forward power trace

     `getKlyFwdPowerAv`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyFwdPowerAv "Permalink to this definition")
    :   Return latest klystron forward power average trace

     `getKlyFwdPowerBuffer`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyFwdPowerBuffer "Permalink to this definition")
    :   Return buffer of klystron forward power rf\_trace objects

     `getKlyFwdPowerData`{.descname}(*(liberaLLRFController)arg1*) → rf\_trace :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyFwdPowerData "Permalink to this definition")
    :   Return latest klystron forward power rf\_trace object

     `getKlyRevPhase`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyRevPhase "Permalink to this definition")
    :   Return latest klystron reverse phase trace

     `getKlyRevPhaseAv`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyRevPhaseAv "Permalink to this definition")
    :   Return latest klystron reverse phase average trace

     `getKlyRevPhaseBuffer`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyRevPhaseBuffer "Permalink to this definition")
    :   Return buffer of klystron reverse phase rf\_trace objects

     `getKlyRevPhaseData`{.descname}(*(liberaLLRFController)arg1*) → rf\_trace :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyRevPhaseData "Permalink to this definition")
    :   Return latest klystron reverse phase rf\_trace object

     `getKlyRevPower`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyRevPower "Permalink to this definition")
    :   Return latest klystron reverse power trace

     `getKlyRevPowerAv`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyRevPowerAv "Permalink to this definition")
    :   Return latest klystron reverse power average trace

     `getKlyRevPowerBuffer`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyRevPowerBuffer "Permalink to this definition")
    :   Return buffer of klystron reverse power rf\_trace objects

     `getKlyRevPowerData`{.descname}(*(liberaLLRFController)arg1*) → rf\_trace :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getKlyRevPowerData "Permalink to this definition")
    :   Return latest klystron reverse power rf\_trace object

     `getLLRFObjConstRef`{.descname}(*(liberaLLRFController)name*) → liberallrfObject :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getLLRFObjConstRef "Permalink to this definition")
    :   Return LLRF Object Reference

     `getLoMask`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getLoMask "Permalink to this definition")
    :   Get Low mask for trace ‘name’

     `getNumOutsideMaskTraces`{.descname}(*(liberaLLRFController)arg1*) → int :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getNumOutsideMaskTraces "Permalink to this definition")
    :   Return the Number of elements in outside\_mask\_traces

     `getNumRollingAverageTraces`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → int :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getNumRollingAverageTraces "Permalink to this definition")
    :   Get the number of traces to average for trace ‘name’

     `getOutsideMaskData`{.descname}(*(liberaLLRFController)arg1*) → dict :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getOutsideMaskData "Permalink to this definition")
    :   Return Saved Data of traces outside masks

        getOutsideMaskData( (liberaLLRFController)arg1, (int)parte) -\> dict :
        :   Return index [part] from saved data of traces outside masks

     `getPhiCalibration`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getPhiCalibration "Permalink to this definition")
    :   Return Linear Conversion of Phase from LLRF units to degrees

     `getPhiDEG`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getPhiDEG "Permalink to this definition")
    :   Get Current Phase relative to Crest [degrees] +ve sense?

     `getPhiFF`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getPhiFF "Permalink to this definition")
    :   Return the Phase(FF) in LLRF Units

     `getPhiLLRF`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getPhiLLRF "Permalink to this definition")
    :   Return the Phase in LLRF Units

     `getPhiSP`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getPhiSP "Permalink to this definition")
    :   Return the Phase(SP) in LLRF Units

     `getProbePhase`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getProbePhase "Permalink to this definition")
    :   Return cavity probe phase

     `getProbePhaseAv`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getProbePhaseAv "Permalink to this definition")
    :   Return cavity probe phase average

     `getProbePower`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getProbePower "Permalink to this definition")
    :   Return cavity probe power

     `getProbePowerAv`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getProbePowerAv "Permalink to this definition")
    :   Return cavity probe power average

     `getPulseLength`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getPulseLength "Permalink to this definition")
    :   Return RF pulse length [micro-s]

     `getPulseOffset`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getPulseOffset "Permalink to this definition")
    :   Return RF Pulse Offset [micro-s]

     `getShotCount`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → int :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getShotCount "Permalink to this definition")
    :   Get Number of traces recieved by this controller for trace
        ‘name’

     `getTraceBuffer`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getTraceBuffer "Permalink to this definition")
    :   Return buffer of rf\_trace objects for channel ‘name’

     `getTraceData`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → rf\_trace :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getTraceData "Permalink to this definition")
    :   Return latest rf\_trace object for Channel ‘name’

     `getTraceLength`{.descname}(*(liberaLLRFController)arg1*) → int :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getTraceLength "Permalink to this definition")
    :   Return Number of elements in a power trace

     `getTraceNames`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getTraceNames "Permalink to this definition")
    :   Return Trace names (defined in config file)

     `getTraceValues`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getTraceValues "Permalink to this definition")
    :   Return latest Trace Values for channel ‘name’

     `getTracesToSaveOnBreakDown`{.descname}(*(liberaLLRFController)arg1*) → list :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getTracesToSaveOnBreakDown "Permalink to this definition")
    :   Get the Names of Traces to Save when a break down occurs

     `getType`{.descname}(*(liberaLLRFController)arg1*) → LLRF\_TYPE :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.getType "Permalink to this definition")
    :   Return the Type of LLRF controller.

     `get_CA_PEND_IO_TIMEOUT`{.descname}(*(liberaLLRFController)arg1*) → float :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.get_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   Time before Timeout when getting values

     `interlockActive`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.interlockActive "Permalink to this definition")
    :   Return true if interlock is Active.

     `interlockNotActive`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.interlockNotActive "Permalink to this definition")
    :   Return true if interlock is not Active.

     `isCheckingMask`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.isCheckingMask "Permalink to this definition")
    :   Is trace ‘name’ checking against a mask?

        isCheckingMask( (liberaLLRFController)arg1, (LLRF\_PV\_TYPE)LLRF\_PV\_TYPE) -\> bool :
        :   Is this LLRF\_PV\_TYPE checking against a mask?

     `isFFLocked`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.isFFLocked "Permalink to this definition")
    :   Return true if FF check box is checked.

     `isFFNotLocked`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.isFFNotLocked "Permalink to this definition")
    :   Return true if FF check box is not checked.

     `isMonitoring`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.isMonitoring "Permalink to this definition")
    :   Is the trace ‘name’ being monitored?

        isMonitoring( (liberaLLRFController)arg1, (LLRF\_PV\_TYPE)LLRF\_PV\_TYPE) -\> bool :
        :   Is this LLRF\_PV\_TYPE being monitored?

     `isNotCheckingMask`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.isNotCheckingMask "Permalink to this definition")
    :   Is trace ‘name’ NOT Checking against a mask?

        isNotCheckingMask( (liberaLLRFController)arg1, (LLRF\_PV\_TYPE)LLRF\_PV\_TYPE) -\> bool :
        :   Is trace LLRF\_PV\_TYPE NOT Checking against a mask?

     `isNotMonitoring`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.isNotMonitoring "Permalink to this definition")
    :   Is the trace ‘name’ NOT being monitored?

        isNotMonitoring( (liberaLLRFController)arg1, (LLRF\_PV\_TYPE)LLRF\_PV\_TYPE) -\> bool :
        :   Is this LLRF\_PV\_TYPE NOT being monitored?

     `isNotTracePV`{.descname}(*(liberaLLRFController)arg1*, *(LLRF\_PV\_TYPE)LLRF\_PV\_TYPE*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.isNotTracePV "Permalink to this definition")
    :   Is this LLRF\_PV\_TYPE NOT a power trace?

     `isTracePV`{.descname}(*(liberaLLRFController)arg1*, *(LLRF\_PV\_TYPE)LLRF\_PV\_TYPE*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.isTracePV "Permalink to this definition")
    :   Is this LLRF\_PV\_TYPE a power trace?

     `offsetTimer`{.descname}(*(liberaLLRFController)arg1*, *(long)arg2*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.offsetTimer "Permalink to this definition")
    :   offeswt the timer by an integer amount

     `resetAverageTraces`{.descname}(*(liberaLLRFController)arg1*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.resetAverageTraces "Permalink to this definition")
    :   Reset All Rolling Averages

     `setAbsoluteMask`{.descname}(*(liberaLLRFController)arg1*, *(int)s1*, *(int)s2*, *(int)s3*, *(int)s4*, *(float)value*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setAbsoluteMask "Permalink to this definition")
    :   Set the mask for trace ‘name’

     `setAllTraceSCAN`{.descname}(*(liberaLLRFController)arg1*, *(LLRF\_SCAN)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setAllTraceSCAN "Permalink to this definition")
    :   Set all monitoring traces SCAN rate to ‘value’

     `setAmpCalibration`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setAmpCalibration "Permalink to this definition")
    :   Set linear calibration of amplitude from LLRF units to MV/m

     `setAmpFF`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setAmpFF "Permalink to this definition")
    :   Set Amplitude(FF) in LLRF Units

     `setAmpLLRF`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setAmpLLRF "Permalink to this definition")
    :   Set Amplitude in LLRF units

     `setAmpMVM`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setAmpMVM "Permalink to this definition")
    :   Set Cavity Amplitude [MV/m]

     `setAmpSP`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setAmpSP "Permalink to this definition")
    :   Set Amplitude(SP) in LLRF Units

     `setCavFwdPwrMaskAbsolute`{.descname}(*(liberaLLRFController)arg1*, *(int)s1*, *(int)s2*, *(int)s3*, *(int)s4*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setCavFwdPwrMaskAbsolute "Permalink to this definition")
    :   set the Cavity Forward Power Mask based on the rolling\_average
        for cavity\_rev\_power trace/nbetween element 0 and s1 will be
        set to default hi/lo (+/-infinity)/nbetween element s1+1 and s2
        will be set by rolling\_average +/- value/nbetween element s2+1
        and s3 will be set very default hi/lo (+/-infinity)/nbetween
        element s3+1 and s4 will be set by rolling\_average +/-
        value/nbetween element s3+1 and s4 will be set very default
        hi/lo (+/-infinity)/n

     `setCavFwdPwrMaskPercent`{.descname}(*(liberaLLRFController)arg1*, *(int)s1*, *(int)s2*, *(int)s3*, *(int)s4*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setCavFwdPwrMaskPercent "Permalink to this definition")
    :   set the Cavity Forward Power Mask based on the rolling\_average
        for cavity\_rev\_power trace/nbetween element 0 and s1 will be
        set to default hi/lo (+/-infinity)/nbetween element s1+1 and s2
        will be set by rolling\_average +/- value percent of
        rolling\_average/nbetween elemnent s2+1 and s3 will be set very
        default hi/lo (+/-infinity)/nbetween element s3+1 and s4 will be
        set by rolling\_average +/- value percent of
        rolling\_average/nbetween element s3+1 and s4 will be set very
        default hi/lo (+/-infinity)/n

     `setCavRevPwrHiMask`{.descname}(*(liberaLLRFController)arg1*, *(list)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setCavRevPwrHiMask "Permalink to this definition")
    :   Set the Hi mask for cavity reverse power (channel defined in
        config file)

     `setCavRevPwrLoMask`{.descname}(*(liberaLLRFController)arg1*, *(list)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setCavRevPwrLoMask "Permalink to this definition")
    :   Set the Lo mask for cavity reverse power (channel defined in
        config file)

     `setCavRevPwrMaskAbsolute`{.descname}(*(liberaLLRFController)arg1*, *(int)s1*, *(int)s2*, *(int)s3*, *(int)s4*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setCavRevPwrMaskAbsolute "Permalink to this definition")
    :   set the Cavity Reverse Power Mask based on the rolling\_average
        for cavity\_rev\_power trace/nbetween element 0 and s1 will be
        set to default hi/lo (+/-infinity)/nbetween element s1+1 and s2
        will be set by rolling\_average +/- value/nbetween element s2+1
        and s3 will be set very default hi/lo (+/-infinity)/nbetween
        element s3+1 and s4 will be set by rolling\_average +/-
        value/nbetween element s3+1 and s4 will be set very default
        hi/lo (+/-infinity)/n

     `setCavRevPwrMaskPercent`{.descname}(*(liberaLLRFController)arg1*, *(int)s1*, *(int)s2*, *(int)s3*, *(int)s4*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setCavRevPwrMaskPercent "Permalink to this definition")
    :   set the Cavity Reverse Power Mask based on the rolling\_average
        for cavity\_rev\_power trace/nbetween element 0 and s1 will be
        set to default hi/lo (+/-infinity)/nbetween element s1+1 and s2
        will be set by rolling\_average +/- value percent of
        rolling\_average/nbetween elemnent s2+1 and s3 will be set very
        default hi/lo (+/-infinity)/nbetween element s3+1 and s4 will be
        set by rolling\_average +/- value percent of
        rolling\_average/nbetween element s3+1 and s4 will be set very
        default hi/lo (+/-infinity)/n

     `setCheckMask`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(bool)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setCheckMask "Permalink to this definition")
    :   Set whether to check (or not check) new traces against the mask
        (pass ‘name’ and true or false)

     `setCrestPhiLLRF`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setCrestPhiLLRF "Permalink to this definition")
    :   Set the Crest Phi value in LLRF Units

     `setDropAmpOnOutsideMaskDetection`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(bool)state*, *(float)amp\_val*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setDropAmpOnOutsideMaskDetection "Permalink to this definition")
    :   Sets the ‘state’ for dropping the llrf amplitude to ‘amp\_val’
        when an outside mask is detected for trace ‘name’, returns true
        on success

     `setDropAmpValue`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(float)amp\_val*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setDropAmpValue "Permalink to this definition")
    :   Sets the value to drop the amplitude to (when enabled) on
        detecting an outside mask trace for trace ‘name’ returns true on
        success

     `setGlobalCheckMask`{.descname}(*(liberaLLRFController)arg1*, *(bool)value*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setGlobalCheckMask "Permalink to this definition")
    :   Set Global check mask flag to ‘value’

     `setGlobalShouldCheckMask`{.descname}(*(liberaLLRFController)arg1*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setGlobalShouldCheckMask "Permalink to this definition")
    :   Set Global check mask flag to True

     `setGlobalShouldNotCheckMask`{.descname}(*(liberaLLRFController)arg1*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setGlobalShouldNotCheckMask "Permalink to this definition")
    :   Set Global check mask flag to False

     `setHighMask`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(list)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setHighMask "Permalink to this definition")
    :   Set the Hi mask for trace ‘name’

        setHighMask( (liberaLLRFController)arg1, (str)name, (std\_vector\_double)value) -\> bool :
        :   Set the Hi mask for trace ‘name’

     `setKeepRollingAverage`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(bool)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setKeepRollingAverage "Permalink to this definition")
    :   Set whetrher to keep a rolling average of previous traces (pass
        ‘name’ and true or false)

     `setLowMask`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(list)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setLowMask "Permalink to this definition")
    :   Set the Lo mask for trace ‘name’

        setLowMask( (liberaLLRFController)arg1, (str)name, (std\_vector\_double)value) -\> bool :
        :   Set the Lo mask for trace ‘name’

     `setMaskFloor`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setMaskFloor "Permalink to this definition")
    :   Set the mask floor for trace ‘name’

     `setMeanStartIndex`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(int)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setMeanStartIndex "Permalink to this definition")
    :   Set trace ‘name’ start index for mean calculation

     `setMeanStopIndex`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(int)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setMeanStopIndex "Permalink to this definition")
    :   Set trace ‘name’ stop index for mean calculation

     `setNumBufferTraces`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(int)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setNumBufferTraces "Permalink to this definition")
    :   Set the number of buffer traces to keep for trace ‘name’ to
        ‘value’

        setNumBufferTraces( (liberaLLRFController)arg1, (int)value) -\> None :
        :   Set the number of buffer traces for all traces to ‘value’

     `setNumContinuousOutsideMaskCount`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(int)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setNumContinuousOutsideMaskCount "Permalink to this definition")
    :   Set the number of continuous outside mask hits to trigger event,
        for trace ‘name’

     `setNumRollingAverageTraces`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(int)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setNumRollingAverageTraces "Permalink to this definition")
    :   Set the number of traces used for the rolling average

        setNumRollingAverageTraces( (liberaLLRFController)arg1, (int)name) -\> None :
        :   Set the number of traces used for the rolling average

     `setPercentMask`{.descname}(*(liberaLLRFController)arg1*, *(int)s1*, *(int)s2*, *(int)s3*, *(int)s4*, *(float)value*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setPercentMask "Permalink to this definition")
    :   Set the mask for trace ‘name’

     `setPhiCalibration`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setPhiCalibration "Permalink to this definition")
    :   Set linear calibration of phase from LLRF units to degrees

     `setPhiDEG`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setPhiDEG "Permalink to this definition")
    :   Set Cavity Phase Relative to Creset [degrees] (+ve sense?)

     `setPhiFF`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setPhiFF "Permalink to this definition")
    :   Set Phase(FF) in LLRF Units

     `setPhiLLRF`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setPhiLLRF "Permalink to this definition")
    :   Set Phase in LLRF Units

     `setPhiSP`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setPhiSP "Permalink to this definition")
    :   Set Phase(SP) in LLRF Units

     `setPulseLength`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setPulseLength "Permalink to this definition")
    :   Set RF pulse length [micro-s]

     `setPulseOffset`{.descname}(*(liberaLLRFController)arg1*, *(float)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setPulseOffset "Permalink to this definition")
    :   Set RF pulse offset [micro-sec]

     `setShouldCheckMask`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setShouldCheckMask "Permalink to this definition")
    :   Set check mask to true for trace ‘name’

     `setShouldKeepRollingAverage`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setShouldKeepRollingAverage "Permalink to this definition")
    :   Set keep rolling average to true for trace ‘name’

        setShouldKeepRollingAverage( (liberaLLRFController)arg1) -\> None :
        :   Set keep rolling average to true for all traces

     `setShouldNotCheckMask`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setShouldNotCheckMask "Permalink to this definition")
    :   Set check mask to false for trace ‘name’

     `setShouldNotKeepRollingAverage`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setShouldNotKeepRollingAverage "Permalink to this definition")
    :   Set keep rolling average to false for trace ‘name’

        setShouldNotKeepRollingAverage( (liberaLLRFController)arg1) -\> None :
        :   Set keep rolling average to false for all traces

     `setTraceSCAN`{.descname}(*(liberaLLRFController)arg1*, *(str)name*, *(LLRF\_SCAN)value*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setTraceSCAN "Permalink to this definition")
    :   Set trace ‘name’ SCAN rate to ‘value’ (if monitoring)

     `setTracesToSaveOnBreakDown`{.descname}(*(liberaLLRFController)arg1*, *(list)arg2*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.setTracesToSaveOnBreakDown "Permalink to this definition")
    :   Set the Names of Traces to Save when a break down occurs

     `set_CA_PEND_IO_TIMEOUT`{.descname}(*(liberaLLRFController)arg1*, *(float)arg2*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.set_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   Time before Timeout when setting values

     `shouldCheckMasks`{.descname}(*(liberaLLRFController)arg1*, *(str)name*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.shouldCheckMasks "Permalink to this definition")
    :   return true if checking masks for trace ‘name’

     `startCavFwdTraceMonitor`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.startCavFwdTraceMonitor "Permalink to this definition")
    :   Start Cavity Forward Power Trace Monitoring

     `startCavRevTraceMonitor`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.startCavRevTraceMonitor "Permalink to this definition")
    :   Start Cavity Reverse Power Trace Monitoring

     `startKlyFwdTraceMonitor`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.startKlyFwdTraceMonitor "Permalink to this definition")
    :   Start Klystron Forward Power Trace Monitoring

     `startKlyRevTraceMonitor`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.startKlyRevTraceMonitor "Permalink to this definition")
    :   Start Klystron Reverse Power Trace Monitoring

     `startTimer`{.descname}(*(liberaLLRFController)arg1*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.startTimer "Permalink to this definition")
    :   Starts (or resets) a local timer

     `startTraceMonitoring`{.descname}(*(liberaLLRFController)arg1*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.startTraceMonitoring "Permalink to this definition")
    :   Start all LLRF Trace Monitors

        startTraceMonitoring( (liberaLLRFController)arg1, (LLRF\_PV\_TYPE)LLRF\_PV\_TYPE) -\> bool :
        :   Start Trace Monitoring for LLRF\_PV\_TYPE
        startTraceMonitoring( (liberaLLRFController)arg1, (str)name) -\> bool :
        :   Start Trace Monitoring for ‘name’

     `stopCavFwdTraceMonitor`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.stopCavFwdTraceMonitor "Permalink to this definition")
    :   Stop Cavity Forward Power Trace Monitoring

     `stopCavRevTraceMonitor`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.stopCavRevTraceMonitor "Permalink to this definition")
    :   Stop Cavity Reverse Power Trace Monitoring

     `stopKlyFwdTraceMonitor`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.stopKlyFwdTraceMonitor "Permalink to this definition")
    :   Stop Klystron Forward Power Trace Monitoring

     `stopKlyRevTraceMonitor`{.descname}(*(liberaLLRFController)arg1*) → bool :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.stopKlyRevTraceMonitor "Permalink to this definition")
    :   Stop Klystron Reverse Power Trace Monitoring

     `stopTraceMonitoring`{.descname}(*(liberaLLRFController)arg1*) → None :[¶](#VELA_CLARA_LLRF_Control.liberaLLRFController.stopTraceMonitoring "Permalink to this definition")
    :   Stop all LLRF Trace Monitors

        stopTraceMonitoring( (liberaLLRFController)arg1, (LLRF\_PV\_TYPE)LLRF\_PV\_TYPE) -\> bool :
        :   Stop Trace Monitoring for LLRF\_PV\_TYPE
        stopTraceMonitoring( (liberaLLRFController)arg1, (str)name) -\> bool :
        :   Stop Trace Monitoring for trace ‘name’

 *class*`VELA_CLARA_LLRF_Control.`{.descclassname}`liberallrfObject`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject "Permalink to this definition")
:   liberallrfObject Doc String: LLRF virtual hardware object data
    members

     `activePulseCount`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.activePulseCount "Permalink to this definition")
    :   (Total) Number of pulses with amp \> 0 since connection.

     `ampCalibration`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.ampCalibration "Permalink to this definition")
    :   Linear Amplitude LLRF units to MV/m

     `amp_MVM`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.amp_MVM "Permalink to this definition")
    :   Current Amplitude in MV/m.

     `amp_drop_value`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.amp_drop_value "Permalink to this definition")
    :   (when enabled) amp value to set on detecting outside mask trace.

     `amp_ff`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.amp_ff "Permalink to this definition")
    :   Current Libera Amplitude FF.

     `amp_sp`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.amp_sp "Permalink to this definition")
    :   Current Libera Amplitude SP.

     `breakdown_rate`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.breakdown_rate "Permalink to this definition")
    :   estimate of number breakdowns per second.

     `crestPhi`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.crestPhi "Permalink to this definition")
    :   Crest Phase.

     `drop_amp_on_breakdown`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.drop_amp_on_breakdown "Permalink to this definition")
    :   If the amplitude should automatically be changed on detecting an
        outside mask trace.

     `ff_amp_lock_state`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.ff_amp_lock_state "Permalink to this definition")
    :   status of the the amplitide FF check box.

     `ff_ph_lock_state`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.ff_ph_lock_state "Permalink to this definition")
    :   status of the the phase FF check box.

     `interlock_state`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.interlock_state "Permalink to this definition")
    :   Libera interlock state.

     `maxAmp`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.maxAmp "Permalink to this definition")
    :   Maximum Amplitude Setting.

     `name`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.name "Permalink to this definition")
    :   LLRF Object Name

     `num_outside_mask_traces`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.num_outside_mask_traces "Permalink to this definition")
    :   The number of outside\_mask\_traces.

     `outside_mask_traces`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.outside_mask_traces "Permalink to this definition")
    :   The saved outside\_mask\_traces, stored in a vector of
        outside\_mask\_trace objects.

     `phiCalibration`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.phiCalibration "Permalink to this definition")
    :   Linear Phase in LLRF units to degrees

     `phi_DEG`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.phi_DEG "Permalink to this definition")
    :   Current Phase in degrees relative to crestPhi.

     `phi_ff`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.phi_ff "Permalink to this definition")
    :   Current Libera Phase FF.

     `phi_sp`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.phi_sp "Permalink to this definition")
    :   Current Libera Phase SP.

     `pulseCount`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.pulseCount "Permalink to this definition")
    :   EVID as number.

     `pulse_latency`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.pulse_latency "Permalink to this definition")
    :   The number of elements in a pulse trace before the RF pulse is
        active (approx.).

     `pulse_length`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.pulse_length "Permalink to this definition")
    :   LLRF RF pulse length

     `pulse_offset`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.pulse_offset "Permalink to this definition")
    :   LLRF RF pulse offset

     `pvRoot`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.pvRoot "Permalink to this definition")
    :   PV root

     `rf_output`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.rf_output "Permalink to this definition")
    :   LLRF RF Output Status

     `time_vector`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.time_vector "Permalink to this definition")
    :   The time vector, stored in a rf\_trace\_data object.

     `timer_start`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.timer_start "Permalink to this definition")
    :   ms since epoch since timer was started.

     `traceLength`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.traceLength "Permalink to this definition")
    :   Number of elements in a trace.

     `trace_data`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.trace_data "Permalink to this definition")
    :   Map of rf\_trace\_data objects, keyed by the Trace Name (defined
        in config file).

     `tracesToSaveOnBreakDown`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.tracesToSaveOnBreakDown "Permalink to this definition")
    :   The names of the traces to save on break down event.

     `type`{.descname}[¶](#VELA_CLARA_LLRF_Control.liberallrfObject.type "Permalink to this definition")
    :   LLRF Controller Type.

 *class*`VELA_CLARA_LLRF_Control.`{.descclassname}`outside_mask_trace`{.descname}[¶](#VELA_CLARA_LLRF_Control.outside_mask_trace "Permalink to this definition")
:   outside\_mask\_trace Doc String

     `high_mask`{.descname}[¶](#VELA_CLARA_LLRF_Control.outside_mask_trace.high_mask "Permalink to this definition")
    :   High mask values

     `low_mask`{.descname}[¶](#VELA_CLARA_LLRF_Control.outside_mask_trace.low_mask "Permalink to this definition")
    :   Low mask values

     `rf_trace`{.descname}[¶](#VELA_CLARA_LLRF_Control.outside_mask_trace.rf_trace "Permalink to this definition")
    :   rf\_trace object

     `time`{.descname}[¶](#VELA_CLARA_LLRF_Control.outside_mask_trace.time "Permalink to this definition")
    :   ms (approx) between timner start and trace flagged

     `trace_name`{.descname}[¶](#VELA_CLARA_LLRF_Control.outside_mask_trace.trace_name "Permalink to this definition")
    :   Channel name trace came from

 *class*`VELA_CLARA_LLRF_Control.`{.descclassname}`rf_trace`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace "Permalink to this definition")
:   rf\_trace Doc String

     `EVID`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace.EVID "Permalink to this definition")
    :   Trace EVID string

     `EVID_time`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace.EVID_time "Permalink to this definition")
    :   Trace EVID time in ns since the epoch

     `EVID_timeStr`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace.EVID_timeStr "Permalink to this definition")
    :   Trace EVID time as a string

     `mean`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace.mean "Permalink to this definition")
    :   mean pwoer between mean\_start\_index and mean\_stop\_index.

     `mean_start_index`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace.mean_start_index "Permalink to this definition")
    :   start index for mean trace calculation.

     `mean_stop_index`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace.mean_stop_index "Permalink to this definition")
    :   stop index for mean trace calculation.

     `time`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace.time "Permalink to this definition")
    :   Epics TimeStamp ns since epoch (double)

     `timeStr`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace.timeStr "Permalink to this definition")
    :   Epics TimeStamp ns since epoch (string)

     `value`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace.value "Permalink to this definition")
    :   trace values

 *class*`VELA_CLARA_LLRF_Control.`{.descclassname}`rf_trace_data`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data "Permalink to this definition")
:   rf\_trace\_data object Doc-String

     `EVID`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.EVID "Permalink to this definition")
    :   Latest EVID for this trace.

     `amp_drop_value`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.amp_drop_value "Permalink to this definition")
    :   (when enabled) amp value to set on detecting outside mask trace.

     `average_size`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.average_size "Permalink to this definition")
    :   number of traces to average

     `buffersize`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.buffersize "Permalink to this definition")
    :   number of traces in buffer

     `check_mask`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.check_mask "Permalink to this definition")
    :   should check mask

     `drop_amp_on_breakdown`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.drop_amp_on_breakdown "Permalink to this definition")
    :   If the amplitude should automatically be changed on detecting an
        outside mask trace.

     `has_average`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.has_average "Permalink to this definition")
    :   has the trace calcualted an an average yet?

     `hi_mask_set`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.hi_mask_set "Permalink to this definition")
    :   is hi mask set

     `high_mask`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.high_mask "Permalink to this definition")
    :   high mask values

     `keep_rolling_average`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.keep_rolling_average "Permalink to this definition")
    :   should keep rolling average

     `latest_trace_index`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.latest_trace_index "Permalink to this definition")
    :   Latest EVID for this trace.

     `low_mask`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.low_mask "Permalink to this definition")
    :   low mask values

     `low_mask_set`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.low_mask_set "Permalink to this definition")
    :   is low mask set

     `mask_floor`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.mask_floor "Permalink to this definition")
    :   Mask floor level.

     `mean_start_index`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.mean_start_index "Permalink to this definition")
    :   start index for mean trace calculation.

     `mean_stop_index`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.mean_stop_index "Permalink to this definition")
    :   stop index for mean trace calculation.

     `num_continuous_outside_mask_count`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.num_continuous_outside_mask_count "Permalink to this definition")
    :   number of continuous outside mask.

     `rolling_average`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.rolling_average "Permalink to this definition")
    :   rolling average values

     `rolling_max`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.rolling_max "Permalink to this definition")
    :   rolling min values

     `rolling_min`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.rolling_min "Permalink to this definition")
    :   rolling max values

     `rolling_sd`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.rolling_sd "Permalink to this definition")
    :   rolling standard deviation values

     `rolling_sum`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.rolling_sum "Permalink to this definition")
    :   rolling sum values

     `rolling_sum_counter`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.rolling_sum_counter "Permalink to this definition")
    :   Total number of traces that have been added to the rolling sum
        (NOT the number of traces IN the rolling sum)

     `shot`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.shot "Permalink to this definition")
    :   shot number, (currently number of traces since monitoring
        started, in future will be timing system shotnumber?)

     `trace_size`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.trace_size "Permalink to this definition")
    :   number of elements in a trace

     `traces`{.descname}[¶](#VELA_CLARA_LLRF_Control.rf_trace_data.traces "Permalink to this definition")
    :   all trace data in buffer of rf\_trace objects ( stored in c++ as
        std::vector\<llrfStructs::rf\_trace\> does this work?)

VELA\_CLARA\_BPM[¶](#module-VELA_CLARA_BPM_Control "Permalink to this headline")
================================================================================

 *class*`VELA_CLARA_BPM_Control.`{.descclassname}`beamPositionMonitorController`{.descname}[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController "Permalink to this definition")
:   This class contains all the functions in the BPM controller for
    monitoring and controlling PVs

     `debugMessagesOff`{.descname}(*(beamPositionMonitorController)arg1*) → None[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.debugMessagesOff "Permalink to this definition")
    :   

     `debugMessagesOn`{.descname}(*(beamPositionMonitorController)arg1*) → None[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.debugMessagesOn "Permalink to this definition")
    :   

     `getBPMNames`{.descname}(*(beamPositionMonitorController)arg1*) → std\_vector\_string :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMNames "Permalink to this definition")
    :   Returns all of the BPM names defined in the config file.

     `getBPMObjectConstRef`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → bpmDataObject :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMObjectConstRef "Permalink to this definition")
    :   Returns the bpm data object for str(bpmName) - these are defined
        in the config file. To be used in conjunction with function
        monitorDataForNShots. Type
        help(VELA\_CLARA\_BPM\_Control.bpmDataObject) to see what this
        contains.

     `getBPMQBuffer`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMQBuffer "Permalink to this definition")
    :   Returns a vector containing the Q values for str(bpmName) -
        these are defined in the config file. To be used in conjunction
        with function monitorDataForNShots.

     `getBPMQVec`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMQVec "Permalink to this definition")
    :   Returns a vector containing the Q values for str(bpmName) -
        these are defined in the config file. To be used in conjunction
        with function monitorDataForNShots.

     `getBPMRawDataStructConstRef`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → rawDataStruct :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMRawDataStructConstRef "Permalink to this definition")
    :   Returns the raw data struct for str(bpmName) - these are defined
        in the config file. To be used in conjunction with function
        monitorDataForNShots. Type
        help(VELA\_CLARA\_BPM\_Control.rawDataStruct) to see what this
        contains.

     `getBPMResolution`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → float :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMResolution "Permalink to this definition")
    :   Returns the resolution (in mm) for str(bpmName) - these are
        defined in the config file. To be used in conjunction with
        function monitorDataForNShots.

     `getBPMXBuffer`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMXBuffer "Permalink to this definition")
    :   Returns a vector containing the X values for str(bpmName) -
        these are defined in the config file. To be used in conjunction
        with function monitorDataForNShots.

     `getBPMXPVBuffer`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMXPVBuffer "Permalink to this definition")
    :   Returns a vector containing the X PV values for str(bpmName) for
        the last (buffersize) values.

     `getBPMXVec`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMXVec "Permalink to this definition")
    :   Returns a vector containing the X values for str(bpmName) -
        these are defined in the config file. To be used in conjunction
        with function monitorDataForNShots.

     `getBPMYBuffer`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMYBuffer "Permalink to this definition")
    :   Returns a vector containing the Y values for str(bpmName) -
        these are defined in the config file. To be used in conjunction
        with function monitorDataForNShots.

     `getBPMYPVBuffer`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMYPVBuffer "Permalink to this definition")
    :   Returns a vector containing the Y PV values for str(bpmName) for
        the last (buffersize) values.

     `getBPMYVec`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getBPMYVec "Permalink to this definition")
    :   Returns a vector containing the Y values for str(bpmName) -
        these are defined in the config file. To be used in conjunction
        with function monitorDataForNShots.

     `getILockStates`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → object :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getILockStates "Permalink to this definition")
    :   Why are you here? BPMs don’t have interlocks. At least as far as
        I’m aware. I’m not sure why they would.

     `getILockStatesDefinition`{.descname}(*(beamPositionMonitorController)arg1*) → dict[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getILockStatesDefinition "Permalink to this definition")
    :   

     `getMachineArea`{.descname}(*(beamPositionMonitorController)arg1*) → MACHINE\_AREA :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getMachineArea "Permalink to this definition")
    :   Returns, as a VELA\_ENUM, the machine area for the controller.

     `getMachineMode`{.descname}(*(beamPositionMonitorController)arg1*) → MACHINE\_MODE :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getMachineMode "Permalink to this definition")
    :   Returns, as a VELA\_ENUM, the machine mode for the controller
        (OFFLINE, PHYSICAL, VIRTUAL).

     `getQ`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → float :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getQ "Permalink to this definition")
    :   Returns (as a float) the current calculated PV of Q for
        str(bpmName) - these are defined in the config file.

     `getRA1`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → int :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getRA1 "Permalink to this definition")
    :   Returns the current EPICS PV of RA1 for str(bpmName) - these are
        defined in the config file.

     `getRA2`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → int :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getRA2 "Permalink to this definition")
    :   Returns the current EPICS PV of RA2 for str(bpmName) - these are
        defined in the config file.

     `getRD1`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → int :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getRD1 "Permalink to this definition")
    :   Returns the current EPICS PV of RD1 for str(bpmName) - these are
        defined in the config file.

     `getRD2`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → int :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getRD2 "Permalink to this definition")
    :   Returns the current EPICS PV of RD2 for str(bpmName) - these are
        defined in the config file.

     `getStrTimeStamps`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getStrTimeStamps "Permalink to this definition")
    :   Returns a vector containing the timestamps as strings (if that’s
        your thing) for str(bpmName) - these are defined in the config
        file. To be used in conjunction with function
        monitorDataForNShots.

     `getTimeStamps`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getTimeStamps "Permalink to this definition")
    :   Returns a vector containing the timestamps as doubles for
        str(bpmName) - these are defined in the config file. To be used
        in conjunction with function monitorDataForNShots.

     `getX`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → float :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getX "Permalink to this definition")
    :   Returns (as a float) the current calculated PV of X for
        str(bpmName) - these are defined in the config file. In theory
        this is more accurate than the EPICS PV.

     `getXFromPV`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → float :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getXFromPV "Permalink to this definition")
    :   Returns (as a float) the current EPICS PV of X for str(bpmName)
        - these are defined in the config file.

     `getY`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → float :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getY "Permalink to this definition")
    :   Returns (as a float) the current calculated PV of Q for
        str(bpmName) - these are defined in the config file.

     `getYFromPV`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → float :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.getYFromPV "Permalink to this definition")
    :   Returns (as a float) the current EPICS PV of Y for str(bpmName)
        - these are defined in the config file.

     `get_CA_PEND_IO_TIMEOUT`{.descname}(*(beamPositionMonitorController)arg1*) → float[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.get_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `isDebugMessageOn`{.descname}(*(beamPositionMonitorController)arg1*) → bool[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.isDebugMessageOn "Permalink to this definition")
    :   

     `isMessageOn`{.descname}(*(beamPositionMonitorController)arg1*) → bool[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.isMessageOn "Permalink to this definition")
    :   

     `isMonitoringBPMData`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.isMonitoringBPMData "Permalink to this definition")
    :   Returns true if str(bpmName) is being monitored - these are
        defined in the config file.

     `isNotMonitoringBPMData`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.isNotMonitoringBPMData "Permalink to this definition")
    :   Returns true if str(bpmName) is not being monitored - these are
        defined in the config file.

     `isSilent`{.descname}(*(beamPositionMonitorController)arg1*) → bool[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.isSilent "Permalink to this definition")
    :   

     `isVerbose`{.descname}(*(beamPositionMonitorController)arg1*) → bool[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.isVerbose "Permalink to this definition")
    :   

     `messagesOff`{.descname}(*(beamPositionMonitorController)arg1*) → None[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.messagesOff "Permalink to this definition")
    :   

     `messagesOn`{.descname}(*(beamPositionMonitorController)arg1*) → None[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.messagesOn "Permalink to this definition")
    :   

     `monitorDataForNShots`{.descname}(*(beamPositionMonitorController)arg1*, *(int)arg2*, *(std\_vector\_string)arg3*) → None :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.monitorDataForNShots "Permalink to this definition")
    :   Monitors raw voltages for str(bpmName) - these are defined in the config file. This will fill up a vector of vectors with shot-to-shot raw voltages.
        :   Data can be accessed using getBPMRawData, getBPMXVec,
            getBPMYVec, getBPMQVec. arg1 is an int, arg2 is a string
        monitorDataForNShots( (beamPositionMonitorController)arg1, (int)arg2, (str)arg3) -\> None :
        :   Monitors raw voltages for std\_vector\_string(str(bpmName))
            - these are defined in the config file. This will fill up a
            vector of vectors with shot-to-shot raw voltages. Data can
            be accessed using getBPMRawData, getBPMXVec, getBPMYVec,
            getBPMQVec. arg1 is an int, arg2 is a std\_vector\_string
            (in python use
            VELA\_CLARA\_BPM\_Control.std\_vector\_string().

     `reCalAttenuation`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*, *(float)arg3*) → None :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.reCalAttenuation "Permalink to this definition")
    :   Re-calibrates the attenuation for str(bpmName) - these are
        defined in the config file - based on a charge reading (arg2).
        The charge reading could be accessed using the scopeController
        module.

     `restartContinuousMonitoring`{.descname}(*(beamPositionMonitorController)arg1*) → None :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.restartContinuousMonitoring "Permalink to this definition")
    :   Restarts continuous monitoring. !!!!!WARNING!!!!! this will
        reset your vectors of values.

     `setBufferSize`{.descname}(*(beamPositionMonitorController)arg1*, *(int)arg2*) → None :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.setBufferSize "Permalink to this definition")
    :   Sets size of the buffer.

     `setSA1`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*, *(int)arg3*) → None :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.setSA1 "Permalink to this definition")
    :   Allows the user to set EPICS PV of SA2 for str(bpmName) - these
        are defined in the config file. arg2 is a long type.

     `setSA2`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*, *(int)arg3*) → None :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.setSA2 "Permalink to this definition")
    :   Allows the user to set EPICS PV of SA2 for str(bpmName) - these
        are defined in the config file. arg2 is a long type.

     `setSD1`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*, *(int)arg3*) → None :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.setSD1 "Permalink to this definition")
    :   Allows the user to set EPICS PV of SD1 for str(bpmName) - these
        are defined in the config file. arg2 is a long type.

     `setSD2`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*, *(int)arg3*) → None :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.setSD2 "Permalink to this definition")
    :   Allows the user to set EPICS PV of SD2 for str(bpmName) - these
        are defined in the config file. arg2 is a long type.

     `setX`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*, *(float)arg3*) → None :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.setX "Permalink to this definition")
    :   Allows the user to set EPICS PV of X for str(bpmName) - these
        are defined in the config file. ONLY FOR THE VIRTUAL MACHINE!!!

     `setY`{.descname}(*(beamPositionMonitorController)arg1*, *(str)arg2*, *(float)arg3*) → None :[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.setY "Permalink to this definition")
    :   Allows the user to set EPICS PV of Y for str(bpmName) - these
        are defined in the config file. ONLY FOR THE VIRTUAL MACHINE!!!

     `set_CA_PEND_IO_TIMEOUT`{.descname}(*(beamPositionMonitorController)arg1*, *(float)arg2*) → None[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.set_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `silence`{.descname}(*(beamPositionMonitorController)arg1*) → None[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.silence "Permalink to this definition")
    :   

     `verbose`{.descname}(*(beamPositionMonitorController)arg1*) → None[¶](#VELA_CLARA_BPM_Control.beamPositionMonitorController.verbose "Permalink to this definition")
    :   

 *class*`VELA_CLARA_BPM_Control.`{.descclassname}`bpmDataObject`{.descname}[¶](#VELA_CLARA_BPM_Control.bpmDataObject "Permalink to this definition")
:   This object contains all of the EPICS PVs for a given bpmName

 *class*`VELA_CLARA_BPM_Control.`{.descclassname}`rawDataStruct`{.descname}[¶](#VELA_CLARA_BPM_Control.rawDataStruct "Permalink to this definition")
:   This struct contains all the ‘raw’ data from the BPMs, including raw
    voltages and timestamps

VELA\_CLARA\_General\_Monitor[¶](#module-VELA_CLARA_General_Monitor "Permalink to this headline")
=================================================================================================

VELA\_CLARA\_Magnet[¶](#module-VELA_CLARA_Magnet_Control "Permalink to this headline")
======================================================================================

 *class*`VELA_CLARA_Magnet_Control.`{.descclassname}`MAG_PSU_STATE`{.descname}[¶](#VELA_CLARA_Magnet_Control.MAG_PSU_STATE "Permalink to this definition")
:   MAG\_PSU\_STATE Doc String

 *class*`VELA_CLARA_Magnet_Control.`{.descclassname}`MAG_REV_TYPE`{.descname}[¶](#VELA_CLARA_Magnet_Control.MAG_REV_TYPE "Permalink to this definition")
:   MAG\_REV\_TYPE Doc String

 *class*`VELA_CLARA_Magnet_Control.`{.descclassname}`MAG_TYPE`{.descname}[¶](#VELA_CLARA_Magnet_Control.MAG_TYPE "Permalink to this definition")
:   MAG\_TYPE Doc String

 *class*`VELA_CLARA_Magnet_Control.`{.descclassname}`magnetController`{.descname}[¶](#VELA_CLARA_Magnet_Control.magnetController "Permalink to this definition")
:   magnetController Doc String

     `applyDBURT`{.descname}(*(magnetController)arg1*, *(str)arg2*) → None[¶](#VELA_CLARA_Magnet_Control.magnetController.applyDBURT "Permalink to this definition")
    :   

     `applyDBURTCorOnly`{.descname}(*(magnetController)arg1*, *(str)arg2*) → None[¶](#VELA_CLARA_Magnet_Control.magnetController.applyDBURTCorOnly "Permalink to this definition")
    :   

     `applyDBURTQuadOnly`{.descname}(*(magnetController)arg1*, *(str)arg2*) → None[¶](#VELA_CLARA_Magnet_Control.magnetController.applyDBURTQuadOnly "Permalink to this definition")
    :   

     `debugMessagesOff`{.descname}(*(magnetController)arg1*) → None[¶](#VELA_CLARA_Magnet_Control.magnetController.debugMessagesOff "Permalink to this definition")
    :   

     `debugMessagesOn`{.descname}(*(magnetController)arg1*) → None[¶](#VELA_CLARA_Magnet_Control.magnetController.debugMessagesOn "Permalink to this definition")
    :   

     `degauss`{.descname}(*(magnetController)arg1*, *(str)magnetname*[, *(bool)degaussToZero=False*]) → int :[¶](#VELA_CLARA_Magnet_Control.magnetController.degauss "Permalink to this definition")
    :   deguass magnetname (single magnet), if degaussToZero = True then
        after degaussing the current will be left at zero, if
        degaussToZero = False the initial current will be reset.

        degauss( (magnetController)arg1, (std\_vector\_string)magnetnames [, (bool)degaussToZero=False]) -\> int :
        :   deguass magnetnames (mulitple magnets), if degaussToZero =
            True then after degaussing the current will be left at zero,
            if degaussToZero = False the initial current will be reset.
        degauss( (magnetController)arg1, (list)magnetnames [, (bool)degaussToZero=False]) -\> int :
        :   deguass magnetnames (mulitple magnets), if degaussToZero =
            True then after degaussing the current will be left at zero,
            if degaussToZero = False the initial current will be reset.

     `getCurrentMagnetState`{.descname}(*(magnetController)arg1*[, *(std\_vector\_string)arg2*]) → magnetStateStruct[¶](#VELA_CLARA_Magnet_Control.magnetController.getCurrentMagnetState "Permalink to this definition")
    :   

     `getDBURT`{.descname}(*(magnetController)arg1*, *(str)arg2*) → magnetStateStruct[¶](#VELA_CLARA_Magnet_Control.magnetController.getDBURT "Permalink to this definition")
    :   

     `getDegValues`{.descname}(*(magnetController)arg1*, *(str)arg2*) → std\_vector\_double[¶](#VELA_CLARA_Magnet_Control.magnetController.getDegValues "Permalink to this definition")
    :   getDegValues( (magnetController)arg1, (std\_vector\_string)arg2)
        -\> object

     `getDipNames`{.descname}(*(magnetController)arg1*) → std\_vector\_string[¶](#VELA_CLARA_Magnet_Control.magnetController.getDipNames "Permalink to this definition")
    :   

     `getFieldIntegralCoefficients`{.descname}(*(magnetController)arg1*, *(str)arg2*) → std\_vector\_double[¶](#VELA_CLARA_Magnet_Control.magnetController.getFieldIntegralCoefficients "Permalink to this definition")
    :   getFieldIntegralCoefficients( (magnetController)arg1,
        (std\_vector\_string)arg2) -\> object

     `getHCorNames`{.descname}(*(magnetController)arg1*) → std\_vector\_string[¶](#VELA_CLARA_Magnet_Control.magnetController.getHCorNames "Permalink to this definition")
    :   

     `getILockStates`{.descname}(*(magnetController)arg1*, *(str)arg2*) → object[¶](#VELA_CLARA_Magnet_Control.magnetController.getILockStates "Permalink to this definition")
    :   

     `getILockStatesDefinition`{.descname}(*(magnetController)arg1*) → dict[¶](#VELA_CLARA_Magnet_Control.magnetController.getILockStatesDefinition "Permalink to this definition")
    :   

     `getMagObjConstRef`{.descname}(*(magnetController)arg1*, *(str)arg2*) → magnetObject[¶](#VELA_CLARA_Magnet_Control.magnetController.getMagObjConstRef "Permalink to this definition")
    :   

     `getMagPSUState`{.descname}(*(magnetController)arg1*, *(str)arg2*) → MAG\_PSU\_STATE[¶](#VELA_CLARA_Magnet_Control.magnetController.getMagPSUState "Permalink to this definition")
    :   getMagPSUState( (magnetController)arg1,
        (std\_vector\_string)arg2) -\> object

     `getMagType`{.descname}(*(magnetController)arg1*, *(str)arg2*) → MAG\_TYPE[¶](#VELA_CLARA_Magnet_Control.magnetController.getMagType "Permalink to this definition")
    :   getMagType( (magnetController)arg1, (std\_vector\_string)arg2)
        -\> std\_vector\_mag\_type

     `getMagnetBranch`{.descname}(*(magnetController)arg1*, *(str)arg2*) → str[¶](#VELA_CLARA_Magnet_Control.magnetController.getMagnetBranch "Permalink to this definition")
    :   getMagnetBranch( (magnetController)arg1,
        (std\_vector\_string)arg2) -\> std\_vector\_string

     `getMagnetNames`{.descname}(*(magnetController)arg1*) → std\_vector\_string[¶](#VELA_CLARA_Magnet_Control.magnetController.getMagnetNames "Permalink to this definition")
    :   

     `getMagneticLength`{.descname}(*(magnetController)arg1*, *(str)arg2*) → float[¶](#VELA_CLARA_Magnet_Control.magnetController.getMagneticLength "Permalink to this definition")
    :   getMagneticLength( (magnetController)arg1,
        (std\_vector\_string)arg2) -\> std\_vector\_double

     `getManufacturer`{.descname}(*(magnetController)arg1*, *(str)arg2*) → str[¶](#VELA_CLARA_Magnet_Control.magnetController.getManufacturer "Permalink to this definition")
    :   getManufacturer( (magnetController)arg1,
        (std\_vector\_string)arg2) -\> std\_vector\_string

     `getMeasurementDataLocation`{.descname}(*(magnetController)arg1*, *(str)arg2*) → str[¶](#VELA_CLARA_Magnet_Control.magnetController.getMeasurementDataLocation "Permalink to this definition")
    :   getMeasurementDataLocation( (magnetController)arg1,
        (std\_vector\_string)arg2) -\> std\_vector\_string

     `getNumDegSteps`{.descname}(*(magnetController)arg1*, *(str)arg2*) → int[¶](#VELA_CLARA_Magnet_Control.magnetController.getNumDegSteps "Permalink to this definition")
    :   getNumDegSteps( (magnetController)arg1,
        (std\_vector\_string)arg2) -\> object

     `getPosition`{.descname}(*(magnetController)arg1*, *(str)arg2*) → float[¶](#VELA_CLARA_Magnet_Control.magnetController.getPosition "Permalink to this definition")
    :   getPosition( (magnetController)arg1, (std\_vector\_string)arg2)
        -\> std\_vector\_double

     `getQuadNames`{.descname}(*(magnetController)arg1*) → std\_vector\_string[¶](#VELA_CLARA_Magnet_Control.magnetController.getQuadNames "Permalink to this definition")
    :   

     `getRI`{.descname}(*(magnetController)arg1*, *(str)arg2*) → float[¶](#VELA_CLARA_Magnet_Control.magnetController.getRI "Permalink to this definition")
    :   getRI( (magnetController)arg1, (std\_vector\_string)arg2) -\>
        std\_vector\_double

     `getRITolerance`{.descname}(*(magnetController)arg1*, *(str)arg2*) → float[¶](#VELA_CLARA_Magnet_Control.magnetController.getRITolerance "Permalink to this definition")
    :   getRITolerance( (magnetController)arg1,
        (std\_vector\_string)arg2) -\> std\_vector\_double

     `getSI`{.descname}(*(magnetController)arg1*, *(str)arg2*) → float[¶](#VELA_CLARA_Magnet_Control.magnetController.getSI "Permalink to this definition")
    :   getSI( (magnetController)arg1, (std\_vector\_string)arg2) -\>
        std\_vector\_double

     `getSerialNumber`{.descname}(*(magnetController)arg1*, *(str)arg2*) → str[¶](#VELA_CLARA_Magnet_Control.magnetController.getSerialNumber "Permalink to this definition")
    :   getSerialNumber( (magnetController)arg1,
        (std\_vector\_string)arg2) -\> std\_vector\_string

     `getSolNames`{.descname}(*(magnetController)arg1*) → std\_vector\_string[¶](#VELA_CLARA_Magnet_Control.magnetController.getSolNames "Permalink to this definition")
    :   

     `getVCorNames`{.descname}(*(magnetController)arg1*) → std\_vector\_string[¶](#VELA_CLARA_Magnet_Control.magnetController.getVCorNames "Permalink to this definition")
    :   

     `get_CA_PEND_IO_TIMEOUT`{.descname}(*(magnetController)arg1*) → float[¶](#VELA_CLARA_Magnet_Control.magnetController.get_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `getmyMachineArea`{.descname}(*(magnetController)arg1*) → MACHINE\_AREA[¶](#VELA_CLARA_Magnet_Control.magnetController.getmyMachineArea "Permalink to this definition")
    :   

     `isABSol`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isABSol "Permalink to this definition")
    :   

     `isACor`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isACor "Permalink to this definition")
    :   

     `isADip`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isADip "Permalink to this definition")
    :   

     `isAHCor`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isAHCor "Permalink to this definition")
    :   

     `isAQuad`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isAQuad "Permalink to this definition")
    :   

     `isASol`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isASol "Permalink to this definition")
    :   

     `isAVCor`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isAVCor "Permalink to this definition")
    :   

     `isDebugMessageOn`{.descname}(*(magnetController)arg1*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isDebugMessageOn "Permalink to this definition")
    :   

     `isDegaussing`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isDegaussing "Permalink to this definition")
    :   

     `isMessageOn`{.descname}(*(magnetController)arg1*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isMessageOn "Permalink to this definition")
    :   

     `isNotDegaussing`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isNotDegaussing "Permalink to this definition")
    :   

     `isOFF`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isOFF "Permalink to this definition")
    :   

     `isON`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isON "Permalink to this definition")
    :   

     `isRIequalSI`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isRIequalSI "Permalink to this definition")
    :   

     `isRIequalVal`{.descname}(*(magnetController)arg1*, *(str)arg2*, *(float)arg3*, *(float)arg4*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isRIequalVal "Permalink to this definition")
    :   

     `isSilent`{.descname}(*(magnetController)arg1*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isSilent "Permalink to this definition")
    :   

     `isVerbose`{.descname}(*(magnetController)arg1*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.isVerbose "Permalink to this definition")
    :   

     `messagesOff`{.descname}(*(magnetController)arg1*) → None[¶](#VELA_CLARA_Magnet_Control.magnetController.messagesOff "Permalink to this definition")
    :   

     `messagesOn`{.descname}(*(magnetController)arg1*) → None[¶](#VELA_CLARA_Magnet_Control.magnetController.messagesOn "Permalink to this definition")
    :   

     `setRITolerance`{.descname}(*(magnetController)arg1*, *(str)arg2*, *(float)arg3*) → None[¶](#VELA_CLARA_Magnet_Control.magnetController.setRITolerance "Permalink to this definition")
    :   setRITolerance( (magnetController)arg1,
        (std\_vector\_string)arg2, (std\_vector\_double)arg3) -\> None

     `setSI`{.descname}(*(magnetController)arg1*, *(str)arg2*, *(float)arg3*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.setSI "Permalink to this definition")
    :   setSI( (magnetController)arg1, (std\_vector\_string)arg2,
        (std\_vector\_double)arg3) -\> bool

        setSI( (magnetController)arg1, (str)arg2, (float)arg3,
        (float)arg4, (int)arg5) -\> bool

        setSI( (magnetController)arg1, (std\_vector\_string)arg2,
        (std\_vector\_double)arg3, (std\_vector\_double)arg4, (int)arg5)
        -\> std\_vector\_string

        setSI( (magnetController)arg1, (list)arg2, (list)arg3) -\> bool

     `setSIZero`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.setSIZero "Permalink to this definition")
    :   setSIZero( (magnetController)arg1, (std\_vector\_string)arg2)
        -\> bool

     `set_CA_PEND_IO_TIMEOUT`{.descname}(*(magnetController)arg1*, *(float)arg2*) → None[¶](#VELA_CLARA_Magnet_Control.magnetController.set_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `silence`{.descname}(*(magnetController)arg1*) → None[¶](#VELA_CLARA_Magnet_Control.magnetController.silence "Permalink to this definition")
    :   

     `switchOFFpsu`{.descname}(*(magnetController)arg1*, *(str)arg2*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.switchOFFpsu "Permalink to this definition")
    :   switchOFFpsu( (magnetController)arg1, (std\_vector\_string)arg2)
        -\> bool

     `switchONpsu`{.descname}(*(magnetController)arg1*, *(str)magnetname*) → bool :[¶](#VELA_CLARA_Magnet_Control.magnetController.switchONpsu "Permalink to this definition")
    :   Switch ON magnetname psu.

        switchONpsu( (magnetController)arg1, (std\_vector\_string)arg2)
        -\> bool

     `verbose`{.descname}(*(magnetController)arg1*) → None[¶](#VELA_CLARA_Magnet_Control.magnetController.verbose "Permalink to this definition")
    :   

     `writeDBURT`{.descname}(*(magnetController)arg1*, *(magnetStateStruct)arg2*, *(str)arg3*, *(str)arg4*, *(str)arg5*) → bool[¶](#VELA_CLARA_Magnet_Control.magnetController.writeDBURT "Permalink to this definition")
    :   writeDBURT( (magnetController)arg1, (str)arg2, (str)arg3,
        (str)arg4) -\> bool

 *class*`VELA_CLARA_Magnet_Control.`{.descclassname}`magnetObject`{.descname}[¶](#VELA_CLARA_Magnet_Control.magnetObject "Permalink to this definition")
:   magnetObject Doc String

 *class*`VELA_CLARA_Magnet_Control.`{.descclassname}`magnetStateStruct`{.descname}[¶](#VELA_CLARA_Magnet_Control.magnetStateStruct "Permalink to this definition")
:   magnetStateStruct Doc String

VELA\_CLARA\_PILaser[¶](#vela-clara-pilaser "Permalink to this headline")
=========================================================================

VELA\_CLARA\_RF\_Modulator[¶](#module-VELA_CLARA_RF_Modulator_Control "Permalink to this headline")
===================================================================================================

 *class*`VELA_CLARA_RF_Modulator_Control.`{.descclassname}`GUN_MOD_STATE`{.descname}[¶](#VELA_CLARA_RF_Modulator_Control.GUN_MOD_STATE "Permalink to this definition")
:   GUN\_MOD\_STATE: a named integer giving the state of the GUN
    Modulator

 *class*`VELA_CLARA_RF_Modulator_Control.`{.descclassname}`L01_MOD_FAULT`{.descname}[¶](#VELA_CLARA_RF_Modulator_Control.L01_MOD_FAULT "Permalink to this definition")
:   L01\_MOD\_FAULT: a named integer giving the fault status of the L01
    Modulator

 *class*`VELA_CLARA_RF_Modulator_Control.`{.descclassname}`L01_MOD_STATE`{.descname}[¶](#VELA_CLARA_RF_Modulator_Control.L01_MOD_STATE "Permalink to this definition")
:   L01\_MOD\_STATE: a named integer giving the state of the L01
    Modulator

 *class*`VELA_CLARA_RF_Modulator_Control.`{.descclassname}`gunModController`{.descname}[¶](#VELA_CLARA_RF_Modulator_Control.gunModController "Permalink to this definition")
:   gunModController Doc String

     `getGunObjConstRef`{.descname}(*(gunModController)arg1*) → gunModObject :[¶](#VELA_CLARA_RF_Modulator_Control.gunModController.getGunObjConstRef "Permalink to this definition")
    :   Return Gun Modulator Object Reference

        C++ signature :
        :   struct rfModStructs::gunModObject getGunObjConstRef(class
            gunModController {lvalue})

 *class*`VELA_CLARA_RF_Modulator_Control.`{.descclassname}`gunModObject`{.descname}[¶](#VELA_CLARA_RF_Modulator_Control.gunModObject "Permalink to this definition")
:   gunModObject Doc String

     `name`{.descname}[¶](#VELA_CLARA_RF_Modulator_Control.gunModObject.name "Permalink to this definition")
    :   LLRF Object Name

     `pvRoot`{.descname}[¶](#VELA_CLARA_RF_Modulator_Control.gunModObject.pvRoot "Permalink to this definition")
    :   PV root

 *class*`VELA_CLARA_RF_Modulator_Control.`{.descclassname}`l01ModController`{.descname}[¶](#VELA_CLARA_RF_Modulator_Control.l01ModController "Permalink to this definition")
:   l01ModController Doc String

     `getObjConstRef`{.descname}(*(l01ModController)arg1*) → l01ModObject :[¶](#VELA_CLARA_RF_Modulator_Control.l01ModController.getObjConstRef "Permalink to this definition")
    :   Return L01 Modulator Object Reference

        C++ signature :
        :   struct rfModStructs::l01ModObject getObjConstRef(class
            l01ModController {lvalue})

     `reset`{.descname}(*(l01ModController)arg1*) → bool :[¶](#VELA_CLARA_RF_Modulator_Control.l01ModController.reset "Permalink to this definition")
    :   C++ signature :
        :   bool reset(class l01ModController {lvalue})

 *class*`VELA_CLARA_RF_Modulator_Control.`{.descclassname}`l01ModObject`{.descname}[¶](#VELA_CLARA_RF_Modulator_Control.l01ModObject "Permalink to this definition")
:   l01ModObject Doc String

     `name`{.descname}[¶](#VELA_CLARA_RF_Modulator_Control.l01ModObject.name "Permalink to this definition")
    :   LLRF Object Name

     `pvRoot`{.descname}[¶](#VELA_CLARA_RF_Modulator_Control.l01ModObject.pvRoot "Permalink to this definition")
    :   PV root

VELA\_CLARA\_RF\_Protection[¶](#vela-clara-rf-protection "Permalink to this headline")
======================================================================================

 *class*`VELA_CLARA_RF_Protection_Control.`{.descclassname}`RF_GUN_PROT_STATUS`{.descname}[¶](#VELA_CLARA_RF_Protection_Control.RF_GUN_PROT_STATUS "Permalink to this definition")
:   RF\_GUN\_PROT\_STATUS: a named integer giving the state of an RF
    protection object

 *class*`VELA_CLARA_RF_Protection_Control.`{.descclassname}`gunProtController`{.descname}[¶](#VELA_CLARA_RF_Protection_Control.gunProtController "Permalink to this definition")
:   DOCSTRING

     `enable`{.descname}()[¶](#VELA_CLARA_RF_Protection_Control.gunProtController.enable "Permalink to this definition")
    :   enable general, current mode and enable, protections, in that
        order

     `getCurrentModeProtName`{.descname}()[¶](#VELA_CLARA_RF_Protection_Control.gunProtController.getCurrentModeProtName "Permalink to this definition")
    :   returns the object name for the current mode protection. Current
        mode depnds on which physical keys are active.

     `getEnableProtName`{.descname}()[¶](#VELA_CLARA_RF_Protection_Control.gunProtController.getEnableProtName "Permalink to this definition")
    :   returns the object name for the enable protection

     `getGeneralProtName`{.descname}()[¶](#VELA_CLARA_RF_Protection_Control.gunProtController.getGeneralProtName "Permalink to this definition")
    :   returns the object name for the general protection

     `getILockStates`{.descname}()[¶](#VELA_CLARA_RF_Protection_Control.gunProtController.getILockStates "Permalink to this definition")
    :   Return the state of interlocks as an integer. There are
        currently NO epics ilocks for the gun protections (in a sense
        the protections ARE the interlocks).

     `getILockStatesStr`{.descname}()[¶](#VELA_CLARA_RF_Protection_Control.gunProtController.getILockStatesStr "Permalink to this definition")
    :   Return state of interlocks as a stringr. There are currently NO
        epics ilocks for the gun protections (in a sense the protections
        ARE the interlocks)

     `getRFProtObjConstRef`{.descname}()[¶](#VELA_CLARA_RF_Protection_Control.gunProtController.getRFProtObjConstRef "Permalink to this definition")
    :   Return RF protection object ‘name’

     `get_CA_PEND_IO_TIMEOUT`{.descname}()[¶](#VELA_CLARA_RF_Protection_Control.gunProtController.get_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   Return the current waiting time [seconds] when sending commands
        to EPICS.

 *class*`VELA_CLARA_RF_Protection_Control.`{.descclassname}`rfGunProtObject`{.descname}[¶](#VELA_CLARA_RF_Protection_Control.rfGunProtObject "Permalink to this definition")
:   rfGunProtObject member variables (read access only)

     `cmi`{.descname}[¶](#VELA_CLARA_RF_Protection_Control.rfGunProtObject.cmi "Permalink to this definition")
    :   object cmi

     `gunProtKeyBitValues`{.descname}[¶](#VELA_CLARA_RF_Protection_Control.rfGunProtObject.gunProtKeyBitValues "Permalink to this definition")
    :   key bit values

     `gunProtKeyBits`{.descname}[¶](#VELA_CLARA_RF_Protection_Control.rfGunProtObject.gunProtKeyBits "Permalink to this definition")
    :   which bits in cmi refer to physcial keys

     `name`{.descname}[¶](#VELA_CLARA_RF_Protection_Control.rfGunProtObject.name "Permalink to this definition")
    :   object name

     `protType`{.descname}[¶](#VELA_CLARA_RF_Protection_Control.rfGunProtObject.protType "Permalink to this definition")
    :   rf gun protection type

     `pvRoot`{.descname}[¶](#VELA_CLARA_RF_Protection_Control.rfGunProtObject.pvRoot "Permalink to this definition")
    :   object pvRoot

     `status`{.descname}[¶](#VELA_CLARA_RF_Protection_Control.rfGunProtObject.status "Permalink to this definition")
    :   object status

VELA\_CLARA\_Scope[¶](#module-VELA_CLARA_Scope_Control "Permalink to this headline")
====================================================================================

 *class*`VELA_CLARA_Scope_Control.`{.descclassname}`scopeController`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeController "Permalink to this definition")
:   scopeController Doc String

     `debugMessagesOff`{.descname}(*(scopeController)arg1*) → None[¶](#VELA_CLARA_Scope_Control.scopeController.debugMessagesOff "Permalink to this definition")
    :   

     `debugMessagesOn`{.descname}(*(scopeController)arg1*) → None[¶](#VELA_CLARA_Scope_Control.scopeController.debugMessagesOn "Permalink to this definition")
    :   

     `getAreaUnderPartOfTrace`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*, *(int)arg4*, *(int)arg5*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getAreaUnderPartOfTrace "Permalink to this definition")
    :   Returns a vector of doubles for str(scopeName), for the channel SCOPE\_PV\_TYPE(pvType), containing the area under a user-specified portion of the trace (between part1 and part2).
        :   The user should specify part1 and part2 to be regions of the
            trace where there is no signal (it may be good to check the
            array size first).
        getAreaUnderPartOfTrace( (scopeController)arg1, (str)arg2, (str)arg3, (int)arg4, (int)arg5) -\> list :
        :   Returns a vector of doubles for str(scopeName), for the
            channel SCOPE\_PV\_TYPE(pvType), containing the area under a
            user-specified portion of the trace (between part1 and
            part2). The user should specify part1 and part2 to be
            regions of the trace where there is no signal (it may be
            good to check the array size first).

     `getAreaUnderTraces`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getAreaUnderTraces "Permalink to this definition")
    :   Returns a vector of doubles for str(scopeName), for the channel SCOPE\_PV\_TYPE(pvType), containing the area under each trace.
        :   This function should only be used after using
            monitorTracesForNShots.
        getAreaUnderTraces( (scopeController)arg1, (str)arg2, (str)arg3) -\> list :
        :   Returns a vector of doubles for str(scopeName), for the
            channel SCOPE\_PV\_TYPE(pvType), containing the area under
            each trace. This function should only be used after using
            monitorTracesForNShots.

     `getAvgNoise`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*, *(int)arg4*, *(int)arg5*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getAvgNoise "Permalink to this definition")
    :   Returns a vector of doubles for str(scopeName), for the channel SCOPE\_PV\_TYPE(pvType), containing the average noise in a user-specified portion of the trace (between part1 and part2).
        :   This function should only be used after using
            monitorTracesForNShots.
        getAvgNoise( (scopeController)arg1, (str)arg2, (str)arg3, (int)arg4, (int)arg5) -\> list :
        :   Returns a vector of doubles for str(scopeName), for the
            channel SCOPE\_PV\_TYPE(pvType), containing the average
            noise in a user-specified portion of the trace (between
            part1 and part2). This function should only be used after
            using monitorTracesForNShots.

     `getEDFCUPQ`{.descname}(*(scopeController)arg1*) → float :[¶](#VELA_CLARA_Scope_Control.scopeController.getEDFCUPQ "Permalink to this definition")
    :   Returns a double containing the current value for the ED-FCUP,
        provided that the ED-FCUP channel is defined in the config file.
        This should work regardless of whether traces or P values are
        being submitted to EPICS.

     `getFCUPQ`{.descname}(*(scopeController)arg1*) → float :[¶](#VELA_CLARA_Scope_Control.scopeController.getFCUPQ "Permalink to this definition")
    :   Returns a double containing the current value for the FCUP,
        provided that the FCUP channel is defined in the config file.
        This should work regardless of whether traces or P values are
        being submitted to EPICS.

     `getICT1Q`{.descname}(*(scopeController)arg1*, *(int)arg2*, *(int)arg3*) → float :[¶](#VELA_CLARA_Scope_Control.scopeController.getICT1Q "Permalink to this definition")
    :   Returns a double containing the current value for the ICT1,
        provided that the ICT1 channel is defined in the config file.
        This should work regardless of whether traces or P values are
        being submitted to EPICS.

     `getICT2Q`{.descname}(*(scopeController)arg1*, *(int)arg2*, *(int)arg3*) → float :[¶](#VELA_CLARA_Scope_Control.scopeController.getICT2Q "Permalink to this definition")
    :   Returns a double containing the current value for the ICT2,
        provided that the ICT2 channel is defined in the config file.
        This should work regardless of whether traces or P values are
        being submitted to EPICS.

     `getMaxOfTraces`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getMaxOfTraces "Permalink to this definition")
    :   Returns a vector of doubles for str(scopeName), for the channel SCOPE\_PV\_TYPE(pvType), containing the maximum value of each trace
        :   This function should only be used after using
            monitorTracesForNShots.
        getMaxOfTraces( (scopeController)arg1, (str)arg2, (str)arg3) -\> list :
        :   Returns a vector of doubles for str(scopeName), for the
            channel SCOPE\_PV\_TYPE(pvType), containing the maximum
            value of each trace This function should only be used after
            using monitorTracesForNShots.

     `getMinOfTraces`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getMinOfTraces "Permalink to this definition")
    :   Returns a vector of doubles for str(scopeName), for the channel SCOPE\_PV\_TYPE(pvType), containing the minimum value of each trace
        :   This function should only be used after using
            monitorTracesForNShots.
        getMinOfTraces( (scopeController)arg1, (str)arg2, (str)arg3) -\> list :
        :   Returns a vector of doubles for str(scopeName), for the
            channel SCOPE\_PV\_TYPE(pvType), containing the minimum
            value of each trace This function should only be used after
            using monitorTracesForNShots.

     `getPartOfTrace`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*, *(int)arg4*, *(int)arg5*) → std\_vector\_vector\_double :[¶](#VELA_CLARA_Scope_Control.scopeController.getPartOfTrace "Permalink to this definition")
    :   Returns a vector of vectors of doubles for str(scopeName), for
        the channel SCOPE\_PV\_TYPE(pvType), of a user-specified portion
        of the trace (between part1 and part2), after using
        monitorTracesForNShots.

        getPartOfTrace( (scopeController)arg1, (str)arg2, (str)arg3, (int)arg4, (int)arg5) -\> std\_vector\_vector\_double :
        :   Returns a vector of vectors of doubles for str(scopeName),
            for the channel SCOPE\_PV\_TYPE(pvType), of a user-specified
            portion of the trace (between part1 and part2), after using
            monitorTracesForNShots.

     `getScopeNames`{.descname}(*(scopeController)arg1*) → list[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeNames "Permalink to this definition")
    :   

     `getScopeNumDataStruct`{.descname}(*(scopeController)arg1*, *(str)arg2*) → scopeNumObject :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeNumDataStruct "Permalink to this definition")
    :   Returns the scope number data struct for str(scopeName). See
        documentation on the scopeNumData struct for what this contains.

     `getScopeNumPVs`{.descname}(*(scopeController)arg1*) → list[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeNumPVs "Permalink to this definition")
    :   

     `getScopeNums`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeNums "Permalink to this definition")
    :   Returns a vector of doubles for str(scopeName), for the channel
        SCOPE\_PV\_TYPE(pvType), after using monitorNumsForNShots.

     `getScopeP1`{.descname}(*(scopeController)arg1*, *(str)arg2*) → float :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP1 "Permalink to this definition")
    :   Returns a double containing the value for channel P1 for
        str(scopeName).

     `getScopeP1Buffer`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP1Buffer "Permalink to this definition")
    :   Returns a vector containing the last (buffersize) values for a
        given channel for str(scopeName).

     `getScopeP1Vec`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP1Vec "Permalink to this definition")
    :   Returns a vector of doubles for str(scopeName), for channel P1,
        after using monitorNumsForNShots.

     `getScopeP2`{.descname}(*(scopeController)arg1*, *(str)arg2*) → float :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP2 "Permalink to this definition")
    :   Returns a double containing the value for channel P2 for
        str(scopeName).

     `getScopeP2Buffer`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP2Buffer "Permalink to this definition")
    :   Returns a vector containing the last (buffersize) values for a
        given channel for str(scopeName).

     `getScopeP2Vec`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP2Vec "Permalink to this definition")
    :   Returns a vector of doubles for str(scopeName), for channel P2,
        after using monitorNumsForNShots.

     `getScopeP3`{.descname}(*(scopeController)arg1*, *(str)arg2*) → float :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP3 "Permalink to this definition")
    :   Returns a double containing the value for channel P3 for
        str(scopeName).

     `getScopeP3Buffer`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP3Buffer "Permalink to this definition")
    :   Returns a vector containing the last (buffersize) values for a
        given channel for str(scopeName).

     `getScopeP3Vec`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP3Vec "Permalink to this definition")
    :   Returns a vector of doubles for str(scopeName), for channel P3,
        after using monitorNumsForNShots.

     `getScopeP4`{.descname}(*(scopeController)arg1*, *(str)arg2*) → float :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP4 "Permalink to this definition")
    :   Returns a double containing the value for channel P4 for
        str(scopeName).

     `getScopeP4Buffer`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP4Buffer "Permalink to this definition")
    :   Returns a vector containing the last (buffersize) values for a
        given channel for str(scopeName).

     `getScopeP4Vec`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeP4Vec "Permalink to this definition")
    :   Returns a vector of doubles for str(scopeName), for channel P4,
        after using monitorNumsForNShots.

     `getScopePVs`{.descname}(*(scopeController)arg1*) → list[¶](#VELA_CLARA_Scope_Control.scopeController.getScopePVs "Permalink to this definition")
    :   

     `getScopeTR1Buffer`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeTR1Buffer "Permalink to this definition")
    :   Returns a vector of vectors containing the last (buffersize)
        traces for a given channel for str(scopeName).

     `getScopeTR2Buffer`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeTR2Buffer "Permalink to this definition")
    :   Returns a vector of vectors containing the last (buffersize)
        traces for a given channel for str(scopeName).

     `getScopeTR3Buffer`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeTR3Buffer "Permalink to this definition")
    :   Returns a vector of vectors containing the last (buffersize)
        traces for a given channel for str(scopeName).

     `getScopeTR4Buffer`{.descname}(*(scopeController)arg1*, *(str)arg2*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeTR4Buffer "Permalink to this definition")
    :   Returns a vector of vectors containing the last (buffersize)
        traces for a given channel for str(scopeName).

     `getScopeTraceDataStruct`{.descname}(*(scopeController)arg1*, *(str)arg2*) → scopeTraceData :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeTraceDataStruct "Permalink to this definition")
    :   Returns the scope trace data struct for str(scopeName). See
        documentation on the scopeTraceData struct for what this
        contains.

     `getScopeTracePVs`{.descname}(*(scopeController)arg1*) → list[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeTracePVs "Permalink to this definition")
    :   

     `getScopeTraces`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*) → std\_vector\_vector\_double :[¶](#VELA_CLARA_Scope_Control.scopeController.getScopeTraces "Permalink to this definition")
    :   Returns a vector of vectors of doubles for str(scopeName), for
        the channel SCOPE\_PV\_TYPE(pvType), after using
        monitorTracesForNShots.

     `getStrTimeStamps`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getStrTimeStamps "Permalink to this definition")
    :   Returns a vector containing the timestamps as strings (if that’s your thing) for str(scope), for the channel SCOPE\_PV\_TYPE(pvType) - these are defined in the config file.
        :   To be used in conjunction with functions
            monitorNumsForNShots or monitorTracesForNShots.
        getStrTimeStamps( (scopeController)arg1, (str)arg2, (str)arg3) -\> list :
        :   Returns a vector containing the timestamps as strings (if
            that’s your thing) for str(scope), for the channel
            SCOPE\_PV\_TYPE(pvType) - these are defined in the config
            file. To be used in conjunction with functions
            monitorNumsForNShots or monitorTracesForNShots.

     `getTimeStamps`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*) → list :[¶](#VELA_CLARA_Scope_Control.scopeController.getTimeStamps "Permalink to this definition")
    :   Returns a vector containing the timestamps as doubles for str(scope), for the channel SCOPE\_PV\_TYPE(pvType) - these are defined in the config file.
        :   To be used in conjunction with functions
            monitorNumsForNShots or monitorTracesForNShots.
        getTimeStamps( (scopeController)arg1, (str)arg2, (str)arg3) -\> list :
        :   Returns a vector containing the timestamps as doubles for
            str(scope), for the channel SCOPE\_PV\_TYPE(pvType) - these
            are defined in the config file. To be used in conjunction
            with functions monitorNumsForNShots or
            monitorTracesForNShots.

     `getWCMQ`{.descname}(*(scopeController)arg1*) → float :[¶](#VELA_CLARA_Scope_Control.scopeController.getWCMQ "Permalink to this definition")
    :   Returns a double containing the current value for the WCM,
        provided that the WCM channel is defined in the config file.
        This should work regardless of whether traces or P values are
        being submitted to EPICS (not for dark current measurements).

     `get_CA_PEND_IO_TIMEOUT`{.descname}(*(scopeController)arg1*) → float[¶](#VELA_CLARA_Scope_Control.scopeController.get_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `isMonitoringScopeNum`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*) → bool :[¶](#VELA_CLARA_Scope_Control.scopeController.isMonitoringScopeNum "Permalink to this definition")
    :   Returns true if str(scopeName) P values are being monitored -
        these are defined in the config file.

     `isMonitoringScopeNums`{.descname}(*(scopeController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Scope_Control.scopeController.isMonitoringScopeNums "Permalink to this definition")
    :   Returns true if str(scopeName) P values are being monitored -
        these are defined in the config file.

     `isMonitoringScopeTrace`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*) → bool :[¶](#VELA_CLARA_Scope_Control.scopeController.isMonitoringScopeTrace "Permalink to this definition")
    :   Returns true if str(scopeName) traces are being monitored -
        these are defined in the config file.

     `isMonitoringScopeTraces`{.descname}(*(scopeController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Scope_Control.scopeController.isMonitoringScopeTraces "Permalink to this definition")
    :   Returns true if str(scopeName) traces are being monitored -
        these are defined in the config file.

     `isNotMonitoringScopeNum`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*) → bool :[¶](#VELA_CLARA_Scope_Control.scopeController.isNotMonitoringScopeNum "Permalink to this definition")
    :   Returns true if str(scopeName) P values are not being monitored
        - these are defined in the config file.

     `isNotMonitoringScopeNums`{.descname}(*(scopeController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Scope_Control.scopeController.isNotMonitoringScopeNums "Permalink to this definition")
    :   Returns true if str(scopeName) P values are not being monitored
        - these are defined in the config file.

     `isNotMonitoringScopeTrace`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*) → bool :[¶](#VELA_CLARA_Scope_Control.scopeController.isNotMonitoringScopeTrace "Permalink to this definition")
    :   Returns true if str(scopeName) P values are not being monitored
        - these are defined in the config file.

     `isNotMonitoringScopeTraces`{.descname}(*(scopeController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Scope_Control.scopeController.isNotMonitoringScopeTraces "Permalink to this definition")
    :   Returns true if str(scopeName) P values are not being monitored
        - these are defined in the config file.

     `messagesOff`{.descname}(*(scopeController)arg1*) → None[¶](#VELA_CLARA_Scope_Control.scopeController.messagesOff "Permalink to this definition")
    :   

     `messagesOn`{.descname}(*(scopeController)arg1*) → None[¶](#VELA_CLARA_Scope_Control.scopeController.messagesOn "Permalink to this definition")
    :   

     `monitorANumForNShots`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*, *(int)arg4*) → None :[¶](#VELA_CLARA_Scope_Control.scopeController.monitorANumForNShots "Permalink to this definition")
    :   Monitors a specific P value (see scope) for channel (pvType) of str(scopeName) - these should be defined in the config file. This will fill a vector of doubles with scope data.
        :   Data can be accessed using getScopeTraces - see
            documentation.
        monitorANumForNShots( (scopeController)arg1, (str)arg2, (str)arg3, (int)arg4) -\> None :
        :   Monitors a specific P value (see scope) for channel (pvType)
            of str(scopeName) - these should be defined in the config
            file. This will fill a vector of doubles with scope data.
            Data can be accessed using getScopeTraces - see
            documentation.

     `monitorATraceForNShots`{.descname}(*(scopeController)arg1*, *(str)arg2*, *(SCOPE\_PV\_TYPE)arg3*, *(int)arg4*) → None :[¶](#VELA_CLARA_Scope_Control.scopeController.monitorATraceForNShots "Permalink to this definition")
    :   Monitors a specific trace (see scope) for channel (pvType) of str(scopeName) - these should be defined in the config file. This will fill a vectors of vectors of doubles with scope trace data.
        :   Data can be accessed using getScopeTraces - see
            documentation.
        monitorATraceForNShots( (scopeController)arg1, (str)arg2, (str)arg3, (int)arg4) -\> None :
        :   Monitors a specific trace (see scope) for channel (pvType)
            of str(scopeName) - these should be defined in the config
            file. This will fill a vectors of vectors of doubles with
            scope trace data. Data can be accessed using getScopeTraces
            - see documentation.

     `monitorNumsForNShots`{.descname}(*(scopeController)arg1*, *(int)arg2*) → None :[¶](#VELA_CLARA_Scope_Control.scopeController.monitorNumsForNShots "Permalink to this definition")
    :   Monitors P values (see scope) for str(scopeName) - these should
        be defined in the config file. This will fill four vectors of
        doubles with scope data. Data can be accessed using
        getScopeNums, or getScopeP(1/2/3/4)Vec.

     `monitorTracesForNShots`{.descname}(*(scopeController)arg1*, *(int)arg2*) → None :[¶](#VELA_CLARA_Scope_Control.scopeController.monitorTracesForNShots "Permalink to this definition")
    :   Monitors traces (see scope) for str(scopeName) - these should be
        defined in the config file. This will fill four vectors of
        vectors of doubles with scope trace data. Data can be accessed
        using getScopeTraces - see documentation.

     `restartContinuousMonitoring`{.descname}(*(scopeController)arg1*) → None :[¶](#VELA_CLARA_Scope_Control.scopeController.restartContinuousMonitoring "Permalink to this definition")
    :   Restarts continuous monitoring of scope parameters. !!!!!!!WILL
        RESET ALL VALUES!!!!!!!.

     `setBufferSize`{.descname}(*(scopeController)arg1*, *(int)arg2*) → None :[¶](#VELA_CLARA_Scope_Control.scopeController.setBufferSize "Permalink to this definition")
    :   Set size of buffer for continuous monitor.

     `setNumBufferSize`{.descname}(*(scopeController)arg1*, *(int)arg2*) → None :[¶](#VELA_CLARA_Scope_Control.scopeController.setNumBufferSize "Permalink to this definition")
    :   Set size of buffer for continuous P values monitor.

     `setTraceBufferSize`{.descname}(*(scopeController)arg1*, *(int)arg2*) → None :[¶](#VELA_CLARA_Scope_Control.scopeController.setTraceBufferSize "Permalink to this definition")
    :   Set size of buffer for continuous trace monitor.

     `set_CA_PEND_IO_TIMEOUT`{.descname}(*(scopeController)arg1*, *(float)arg2*) → None[¶](#VELA_CLARA_Scope_Control.scopeController.set_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `silence`{.descname}(*(scopeController)arg1*) → None[¶](#VELA_CLARA_Scope_Control.scopeController.silence "Permalink to this definition")
    :   

     `verbose`{.descname}(*(scopeController)arg1*) → None[¶](#VELA_CLARA_Scope_Control.scopeController.verbose "Permalink to this definition")
    :   

 *class*`VELA_CLARA_Scope_Control.`{.descclassname}`scopeNumObject`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject "Permalink to this definition")
:   This struct contains data for the four channels on the scope - e.g.
    p1 contains the P1 value from the scope. This will only contain
    real-time data if scope number data is being submitted to EPICS -
    you will need to check this on the scope. p1Vec contains a vector of
    values after monitorNumsForNShots, and numData contains a vector of
    vectors, with data from all four channels on the scope. Timestamps
    can also be accessed.

     `buffer`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.buffer "Permalink to this definition")
    :   The current size of the buffer.

     `isMonitoringMap`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.isMonitoringMap "Permalink to this definition")
    :   Check if monitorNumsForNShots / monitorANumForNShots is still
        acquiring - a map of bools keyed by SCOPE\_PV\_TYPE.

     `name`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.name "Permalink to this definition")
    :   Name of scope.

     `numData`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.numData "Permalink to this definition")
    :   A map of vectors, keyed by SCOPE\_PV\_TYPE, containing the data
        filled after monitorNumsForNShots.

     `numDataBuffer`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.numDataBuffer "Permalink to this definition")
    :   A map of vectors of vectors, keyed by SCOPE\_PV\_TYPE,
        containing the last (buffersize) traces for all channels.

     `p1`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.p1 "Permalink to this definition")
    :   The current P value (e.g. measured charge) for a given
        diagnostic.

     `p1Vec`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.p1Vec "Permalink to this definition")
    :   A vector of P values for a given diagnostic, filled during
        monitorNumsForNShots.

     `p2`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.p2 "Permalink to this definition")
    :   The current P value (e.g. measured charge) for a given
        diagnostic.

     `p2Vec`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.p2Vec "Permalink to this definition")
    :   A vector of P values for a given diagnostic, filled during
        monitorNumsForNShots.

     `p3`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.p3 "Permalink to this definition")
    :   The current P value (e.g. measured charge) for a given
        diagnostic.

     `p3Vec`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.p3Vec "Permalink to this definition")
    :   A vector of P values for a given diagnostic, filled during
        monitorNumsForNShots.

     `p4`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.p4 "Permalink to this definition")
    :   The current P value (e.g. measured charge) for a given
        diagnostic.

     `p4Vec`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.p4Vec "Permalink to this definition")
    :   A vector of P values for a given diagnostic, filled during
        monitorNumsForNShots.

     `pvRoot`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeNumObject.pvRoot "Permalink to this definition")
    :   EPICS PV root name.

 *class*`VELA_CLARA_Scope_Control.`{.descclassname}`scopeTraceData`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeTraceData "Permalink to this definition")
:   This struct contains trace data for the four channels on the scope,
    which can be accessed through traceData[SCOPE\_PV\_TYPE]. This will
    only contain real-time data if scope trace data is being submitted
    to EPICS - you will need to check this on the scope.

     `buffer`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeTraceData.buffer "Permalink to this definition")
    :   The current size of the buffer.

     `isMonitoringMap`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeTraceData.isMonitoringMap "Permalink to this definition")
    :   Check if monitorTracesForNShots / monitorATraceForNShots is
        still acquiring - a map of bools keyed by SCOPE\_PV\_TYPE.

     `name`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeTraceData.name "Permalink to this definition")
    :   Name of scope.

     `pvRoot`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeTraceData.pvRoot "Permalink to this definition")
    :   EPICS PV root name.

     `timebase`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeTraceData.timebase "Permalink to this definition")
    :   The timebase set for the traces - defined in the config file.

     `traceData`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeTraceData.traceData "Permalink to this definition")
    :   A map of vectors of vectors, keyed by SCOPE\_PV\_TYPE,
        containing the data filled after monitorTracesForNShots.

     `traceDataBuffer`{.descname}[¶](#VELA_CLARA_Scope_Control.scopeTraceData.traceDataBuffer "Permalink to this definition")
    :   A map of vectors of vectors, keyed by SCOPE\_PV\_TYPE,
        containing the last (buffersize) traces for all channels.

VELA\_CLARA\_Screen[¶](#vela-clara-screen "Permalink to this headline")
=======================================================================

VELA\_CLARA\_Vac\_Valve[¶](#module-VELA_CLARA_Vac_Valve_Control "Permalink to this headline")
=============================================================================================

 *class*`VELA_CLARA_Vac_Valve_Control.`{.descclassname}`vacValveObject`{.descname}[¶](#VELA_CLARA_Vac_Valve_Control.vacValveObject "Permalink to this definition")
:   vacValveObject Doc String

     `name`{.descname}[¶](#VELA_CLARA_Vac_Valve_Control.vacValveObject.name "Permalink to this definition")
    :   valve name

     `numIlocks`{.descname}[¶](#VELA_CLARA_Vac_Valve_Control.vacValveObject.numIlocks "Permalink to this definition")
    :   

     `pvRoot`{.descname}[¶](#VELA_CLARA_Vac_Valve_Control.vacValveObject.pvRoot "Permalink to this definition")
    :   valve pvRoot

     `vacValveState`{.descname}[¶](#VELA_CLARA_Vac_Valve_Control.vacValveObject.vacValveState "Permalink to this definition")
    :   valve state

 *class*`VELA_CLARA_Vac_Valve_Control.`{.descclassname}`vacuumValveController`{.descname}[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController "Permalink to this definition")
:   This class contains all the functions in the vacuum valve controller
    for monitoring and controlling PVs

     `closeAndWait`{.descname}(*(vacuumValveController)arg1*, *(str)arg2*, *(long)arg3*) → bool :[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeAndWait "Permalink to this definition")
    :   Closes the specified valve (arg1 (string)) and waits for the
        given time (arg2 (time\_t)).

     `closeAndWaitValve1`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeAndWaitValve1 "Permalink to this definition")
    :   

     `closeAndWaitValve2`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeAndWaitValve2 "Permalink to this definition")
    :   

     `closeAndWaitValve3`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeAndWaitValve3 "Permalink to this definition")
    :   

     `closeAndWaitValve4`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeAndWaitValve4 "Permalink to this definition")
    :   

     `closeAndWaitValve5`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeAndWaitValve5 "Permalink to this definition")
    :   

     `closeAndWaitValve6`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeAndWaitValve6 "Permalink to this definition")
    :   

     `closeAndWaitValve7`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeAndWaitValve7 "Permalink to this definition")
    :   

     `closeVacValve`{.descname}(*(vacuumValveController)arg1*, *(str)arg2*) → None :[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeVacValve "Permalink to this definition")
    :   Closes the specified valve (arg1 (string)).

     `closeValve1`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeValve1 "Permalink to this definition")
    :   

     `closeValve2`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeValve2 "Permalink to this definition")
    :   

     `closeValve3`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeValve3 "Permalink to this definition")
    :   

     `closeValve4`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeValve4 "Permalink to this definition")
    :   

     `closeValve5`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeValve5 "Permalink to this definition")
    :   

     `closeValve6`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeValve6 "Permalink to this definition")
    :   

     `closeValve7`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.closeValve7 "Permalink to this definition")
    :   

     `debugMessagesOff`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.debugMessagesOff "Permalink to this definition")
    :   

     `debugMessagesOn`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.debugMessagesOn "Permalink to this definition")
    :   

     `getILockStates`{.descname}(*(vacuumValveController)arg1*, *(str)arg2*) → object :[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.getILockStates "Permalink to this definition")
    :   Returns, a map of valve interlock states, keyed by interlock
        number. .

     `getILockStatesDefinition`{.descname}(*(vacuumValveController)arg1*) → dict[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.getILockStatesDefinition "Permalink to this definition")
    :   

     `getVacValveNames`{.descname}(*(vacuumValveController)arg1*) → std\_vector\_string :[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.getVacValveNames "Permalink to this definition")
    :   Returns, as a vector of strings, the available vacuum valve
        names given in the config file.

     `getVacValveObjConstRef`{.descname}(*(vacuumValveController)arg1*, *(str)arg2*) → vacValveObject[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.getVacValveObjConstRef "Permalink to this definition")
    :   

     `getVacValveState`{.descname}(*(vacuumValveController)arg1*, *(str)arg2*) → VALVE\_STATE :[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.getVacValveState "Permalink to this definition")
    :   Returns (as a VELA\_ENUM) the state of the vacuum valve - open,
        closed, moving, or error.

     `getVacValveStateStr`{.descname}(*(vacuumValveController)arg1*, *(str)arg2*) → str :[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.getVacValveStateStr "Permalink to this definition")
    :   Returns (as a VELA\_ENUM) the state of the vacuum valve - open,
        closed, moving, or error.

     `get_CA_PEND_IO_TIMEOUT`{.descname}(*(vacuumValveController)arg1*) → float[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.get_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `isClosed`{.descname}(*(vacuumValveController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.isClosed "Permalink to this definition")
    :   Checks if the given valve (arg1 (string)) is closed, returns 1
        if yes, 0 if no.

     `isOpen`{.descname}(*(vacuumValveController)arg1*, *(str)arg2*) → bool :[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.isOpen "Permalink to this definition")
    :   Checks if the given valve (arg1 (string)) is open, returns 1 if
        yes, 0 if no.

     `messagesOff`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.messagesOff "Permalink to this definition")
    :   

     `messagesOn`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.messagesOn "Permalink to this definition")
    :   

     `openAndWait`{.descname}(*(vacuumValveController)arg1*, *(str)arg2*, *(long)arg3*) → bool :[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openAndWait "Permalink to this definition")
    :   Opens the specified valve (arg1 (string)) and waits for the
        given time (arg2 (time\_t)).

     `openAndWaitValve1`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openAndWaitValve1 "Permalink to this definition")
    :   

     `openAndWaitValve2`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openAndWaitValve2 "Permalink to this definition")
    :   

     `openAndWaitValve3`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openAndWaitValve3 "Permalink to this definition")
    :   

     `openAndWaitValve4`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openAndWaitValve4 "Permalink to this definition")
    :   

     `openAndWaitValve5`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openAndWaitValve5 "Permalink to this definition")
    :   

     `openAndWaitValve6`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openAndWaitValve6 "Permalink to this definition")
    :   

     `openAndWaitValve7`{.descname}(*(vacuumValveController)arg1*, *(long)arg2*) → bool[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openAndWaitValve7 "Permalink to this definition")
    :   

     `openVacValve`{.descname}(*(vacuumValveController)arg1*, *(str)arg2*) → None :[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openVacValve "Permalink to this definition")
    :   Opens the specified valve (arg1 (string)).

     `openValve1`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openValve1 "Permalink to this definition")
    :   

     `openValve2`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openValve2 "Permalink to this definition")
    :   

     `openValve3`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openValve3 "Permalink to this definition")
    :   

     `openValve4`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openValve4 "Permalink to this definition")
    :   

     `openValve5`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openValve5 "Permalink to this definition")
    :   

     `openValve6`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openValve6 "Permalink to this definition")
    :   

     `openValve7`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.openValve7 "Permalink to this definition")
    :   

     `set_CA_PEND_IO_TIMEOUT`{.descname}(*(vacuumValveController)arg1*, *(float)arg2*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.set_CA_PEND_IO_TIMEOUT "Permalink to this definition")
    :   

     `silence`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.silence "Permalink to this definition")
    :   

     `verbose`{.descname}(*(vacuumValveController)arg1*) → None[¶](#VELA_CLARA_Vac_Valve_Control.vacuumValveController.verbose "Permalink to this definition")
    :   


