# PuzzleTak_AudioWaveSeekBar
# Made by PuzzleTak

## Getting Started

## Demo new

<img src="https://github.com/PuzzleTakX/PuzzleTak_AudioWaveSeekBar/blob/main/photo_2022-08-19_16-01-31.jpg?raw=true" alt="image_demo" width="300" height="700">

- [Manufacturer: PuzzleTak](https://instagram.com/puzzletak)

# Usage
```
	Dim pt As PuzzleTak_AudioWaveSeekBar
	pt.Initialize("pt")
    pt.RandomUUID

	Dim p As Phone
	If p.SdkVersion >= 24 Then
		pt.TreadGetByteUUIDFromBytes(File.DirAssets,"la_la_la.mp3") ' use android 6 up
'		pt.TreadDownloadFileUUIDFromBytes("url music") ' use android 6 up
		Else
			pt.RandomUUID ' support wave rndom ☺♥ support all version android
	End If
	
	pt.setSeekColor(0xFF31A6D5,0x3CB0B0B0,0xFF31A6D5)
	pt.onTouch(2,10,15)
	pt.setSize(80%x,80%y)
	pt.Duration = mp.Duration
	pt.Progress =12000
```

# CallBack Method
```
Sub pt_SeekBarChangeListener(progress As Int)
	Log("progress : "&progress)
End Sub
```
