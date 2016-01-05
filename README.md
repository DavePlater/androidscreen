# androidscreen
screencapture and etc


adb shell screenrecord --verbose --time-limit 30 /sdcard/Movies/01042015.mp4 


@if (@X)==(@Y) @end /* ---Harmless hybrid line that begins a JScript comment

@echo off
cscript //E:JScript //nologo "%~f0"
exit /b 0
*------------------------------------------------------------------------------*/

function GetDateFileName(strPrefix,strSuffix)
{
	var retval=strPrefix;
	var todayDate = new Date();
	retval+=todayDate.getFullYear();
	retval+=("0" + (todayDate.getMonth() + 1)).slice(-2);
	retval+=("0" + todayDate.getDate()).slice(-2);
	retval+=("0" + todayDate.getHours()).slice(-2);
	retval+=("0" + todayDate.getMinutes()).slice(-2);
	retval+=("0" + todayDate.getSeconds()).slice(-2);
	retval+=strSuffix;
	return retval;
}
function GetCurrentDate() {
        // Today date time which will used to set as default date.
        var todayDate = new Date();
        todayDate = todayDate.getFullYear() + "-" +
                       ("0" + (todayDate.getMonth() + 1)).slice(-2) + "-" +
                       ("0" + todayDate.getDate()).slice(-2) + " " + ("0" + todayDate.getHours()).slice(-2) + ":" +
                       ("0" + todayDate.getMinutes()).slice(-2);

        return todayDate;
    }

WScript.Echo(GetDateFileName("vid_",".mp4")); 
