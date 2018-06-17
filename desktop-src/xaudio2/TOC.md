# [XAudio2 APIs](xaudio2-apis-portal.md)
## [Programming Guide](programming-guide.md)
### [XAudio2 Introduction](xaudio2-introduction.md)
### [Common Audio Concepts](common-audio-concepts.md)
#### [Coordinates of 3D Space](coordinates-of-3d-space.md)
#### [Perception of Sound Positions](perception-of-sound-positions.md)
#### [Sound Cones](sound-cones.md)
### [Getting Started](getting-started.md)
#### [XAudio2 Key Concepts](xaudio2-key-concepts.md)
#### [XAudio2 Versions](xaudio2-versions.md)
#### [How to: Initialize XAudio2](how-to--initialize-xaudio2.md)
#### [Resource Interchange File Format (RIFF)](resource-interchange-file-format--riff-.md)
#### [How to: Load Audio Data Files in XAudio2](how-to--load-audio-data-files-in-xaudio2.md)
#### [How to: Play a Sound with XAudio2](how-to--play-a-sound-with-xaudio2.md)
### [Voices](voices.md)
#### [XAudio2 Voices](xaudio2-voices.md)
#### [How to: Use Submix Voices](how-to--use-submix-voices.md)
#### [XAudio2 Sample Rate Conversions](xaudio2-sample-rate-conversions.md)
#### [XAudio2 Default Channel Mapping](xaudio2-default-channel-mapping.md)
#### [Volume and Pitch Control](volume-and-pitch-control.md)
##### [XAudio2 Volume and Pitch Control](xaudio2-volume-and-pitch-control.md)
##### [How to: Change Voice Pitch](how-to--change-voice-pitch.md)
##### [How to: Change Voice Volume](how-to--change-voice-volume.md)
##### [How to: Pan a Sound](how-to--pan-a-sound.md)
### [Callbacks](callbacks.md)
#### [XAudio2 Callbacks](xaudio2-callbacks.md)
#### [How to: Use Source Voice Callbacks](how-to--use-source-voice-callbacks.md)
#### [How to: Use Engine Callbacks](how-to--use-engine-callbacks.md)
### [Audio Graphs](audio-graphs.md)
#### [XAudio2 Audio Graph](xaudio2-audio-graph.md)
#### [How to: Build a Basic Audio Processing Graph](how-to--build-a-basic-audio-processing-graph.md)
#### [How to: Dynamically Add or Remove Voices From an Audio Graph](how-to--dynamically-add-or-remove-voices-from-an-audio-graph.md)
### [Audio Effects](audio-effects.md)
#### [XAudio2 Audio Effects](xaudio2-audio-effects.md)
#### [How to: Create an Effect Chain](how-to--create-an-effect-chain.md)
#### [XAPO Overview](xapo-overview.md)
#### [How to: Create an XAPO](how-to--create-an-xapo.md)
#### [How to: Add Run-time Parameter Support to an XAPO](how-to--add-run-time-parameter-support-to-an-xapo.md)
#### [How to: Use an XAPO in XAudio2](how-to--use-an-xapo-in-xaudio2.md)
#### [XAPOFX Overview](xapofx-overview.md)
#### [How to: Use XAPOFX in XAudio2](how-to--use-xapofx-in-xaudio2.md)
### [Streaming Audio Data](streaming-audio-data.md)
#### [XAudio2 Streaming Audio Data](xaudio2-streaming-audio-data.md)
#### [How to: Stream a Sound from Disk](how-to--stream-a-sound-from-disk.md)
### [X3DAudio](x3daudio.md)
#### [X3DAudio Overview](x3daudio-overview.md)
#### [How to: Integrate X3DAudio with XAudio2](how-to--integrate-x3daudio-with-xaudio2.md)
### [Operation Sets](operation-sets.md)
#### [XAudio2 Operation Sets](xaudio2-operation-sets.md)
#### [How to: Group Audio Methods as an Operation Set](how-to--group-audio-methods-as-an-operation-set.md)
### [Debugging Facilities](debugging-facilities.md)
#### [XAudio2 Debugging Facilities](xaudio2-debugging-facilities.md)
#### [Debugging Audio Glitches in XAudio2](debugging-audio-glitches-in-xaudio2.md)
### [ADPCM Overview](adpcm-overview.md)
## [Programming Reference](programming-reference.md)
### [Classes](classes.md)
#### [CXAPOBase](/windows/desktop/api/XAPOBase/nl-xapobase-cxapobase)
##### [CXAPOBase Members](cxapobase-members.md)
##### [CXAPOBase method](https://msdn.microsoft.com/en-us/library/Ee416373(v=VS.85).aspx)
##### [GetRegistrationPropertiesInternal method](https://msdn.microsoft.com/en-us/library/Ee416375(v=VS.85).aspx)
##### [IsLocked method](https://msdn.microsoft.com/en-us/library/Ee416377(v=VS.85).aspx)
##### [ProcessThru method](https://msdn.microsoft.com/en-us/library/Ee416378(v=VS.85).aspx)
##### [ValidateFormatDefault method](https://msdn.microsoft.com/en-us/library/Ee416380(v=VS.85).aspx)
##### [ValidateFormatPair method](https://msdn.microsoft.com/en-us/library/Ee416382(v=VS.85).aspx)
#### [CXAPOParametersBase](/windows/desktop/api/XAPOBase/nl-xapobase-cxapoparametersbase)
##### [CXAPOParametersBase Members](cxapoparametersbase-members.md)
##### [CXAPOParametersBase method](https://msdn.microsoft.com/en-us/library/Ee416386(v=VS.85).aspx)
##### [BeginProcess method](https://msdn.microsoft.com/en-us/library/Ee416384(v=VS.85).aspx)
##### [EndProcess method](https://msdn.microsoft.com/en-us/library/Ee416388(v=VS.85).aspx)
##### [OnSetParameters method](https://msdn.microsoft.com/en-us/library/Ee416390(v=VS.85).aspx)
##### [ParametersChanged method](https://msdn.microsoft.com/en-us/library/Ee416392(v=VS.85).aspx)
### [Constants](constants.md)
#### [FXECHO Constants](fxecho-constants.md)
#### [FXEQ Constants](fxeq-constants.md)
#### [FXMASTERINGLIMIT Constants](fxmasteringlimit-constants.md)
#### [FXREVERB Constants](fxreverb-constants.md)
#### [XAudio2 Boundary Values and Flags](xaudio2-boundary-values-and-flags.md)
#### [XAudio2 Error Codes](xaudio2-error-codes.md)
#### [XAUDIO2_PROCESSOR](uint32-xaudio2-processor.md)
#### [XAUDIO2FX_I3DL2_PRESET](xaudio2fx-i3dl2-preset.md)
#### [XAUDIO2FX_REVERB_DEFAULT](xaudio2fx-reverb-default.md)
#### [XAUDIO2FX_REVERB_MAX](xaudio2fx-reverb-max.md)
#### [XAUDIO2FX_REVERB_MIN](xaudio2fx-reverb-min.md)
### [Enumerations](enumerations.md)
#### [HrtfDirectivityType](/windows/desktop/api/HrtfApoApi/ne-hrtfapoapi-hrtfdirectivitytype)
#### [HrtfDistanceDecayType](/windows/desktop/api/HrtfApoApi/ne-hrtfapoapi-hrtfdistancedecaytype)
#### [HrtfEnvironment](/windows/desktop/api/HrtfApoApi/ne-hrtfapoapi-hrtfenvironment)
#### [XAUDIO2_FILTER_TYPE](/windows/desktop/api/xaudio2/ne-xaudio2-xaudio2_filter_type)
#### [XAPO_BUFFER_FLAGS](/windows/desktop/api/xapo/ne-xapo-xapo_buffer_flags)
### [Functions](functions.md)
#### [CreateFX](/windows/desktop/api/XAPOFX/nf-xapofx-createfx)
#### [CreateHrtfApo](/windows/desktop/api/HrtfApoApi/nf-hrtfapoapi-createhrtfapo)
#### [ReverbConvertI3DL2ToNative](/windows/desktop/api/xaudio2fx/nf-xaudio2fx-reverbconverti3dl2tonative)
#### [X3DAudioCalculate](/windows/desktop/api/x3daudio/nf-x3daudio-x3daudiocalculate)
#### [X3DAudioInitialize](/windows/desktop/api/x3daudio/nf-x3daudio-x3daudioinitialize)
#### [XAudio2AmplitudeRatioToDecibels](/windows/desktop/api/xaudio2/nf-xaudio2-xaudio2amplituderatiotodecibels)
#### [XAudio2Create](/windows/desktop/api/xaudio2/nf-xaudio2-xaudio2create)
#### [XAudio2CreateReverb](/windows/desktop/api/xaudio2fx/nf-xaudio2fx-xaudio2createreverb)
#### [XAudio2CreateVolumeMeter](/windows/desktop/api/xaudio2fx/nf-xaudio2fx-xaudio2createvolumemeter)
#### [XAudio2CutoffFrequencyToOnePoleCoefficient](/windows/desktop/api/xaudio2/nf-xaudio2-xaudio2cutofffrequencytoonepolecoefficient)
#### [XAudio2CutoffFrequencyToRadians](/windows/desktop/api/xaudio2/nf-xaudio2-xaudio2cutofffrequencytoradians)
#### [XAudio2DecibelsToAmplitudeRatio](/windows/desktop/api/xaudio2/nf-xaudio2-xaudio2decibelstoamplituderatio)
#### [XAudio2FrequencyRatioToSemitones](/windows/desktop/api/xaudio2/nf-xaudio2-xaudio2frequencyratiotosemitones)
#### [XAudio2RadiansToCutoffFrequency](/windows/desktop/api/xaudio2/nf-xaudio2-xaudio2radianstocutofffrequency)
#### [XAudio2SemitonesToFrequencyRatio](/windows/desktop/api/xaudio2/nf-xaudio2-xaudio2semitonestofrequencyratio)
### [Interfaces](interfaces.md)
#### [IXAudio2](/windows/desktop/api/xaudio2/nn-xaudio2-ixaudio2)
##### [AddRef method](https://msdn.microsoft.com/en-us/library/Ee418601(v=VS.85).aspx)
##### [CommitChanges method](https://msdn.microsoft.com/en-us/library/Ee418603(v=VS.85).aspx)
##### [CreateMasteringVoice method](https://msdn.microsoft.com/en-us/library/Hh405048(v=VS.85).aspx)
##### [CreateSourceVoice method](https://msdn.microsoft.com/en-us/library/Ee418607(v=VS.85).aspx)
##### [CreateSubmixVoice method](https://msdn.microsoft.com/en-us/library/Ee418608(v=VS.85).aspx)
##### [GetPerformanceData method](https://msdn.microsoft.com/en-us/library/Ee418615(v=VS.85).aspx)
##### [QueryInterface method](https://msdn.microsoft.com/en-us/library/Ee418619(v=VS.85).aspx)
##### [RegisterForCallbacks method](https://msdn.microsoft.com/en-us/library/Ee418620(v=VS.85).aspx)
##### [Release method](https://msdn.microsoft.com/en-us/library/Ee418622(v=VS.85).aspx)
##### [SetDebugConfiguration method](https://msdn.microsoft.com/en-us/library/Ee418624(v=VS.85).aspx)
##### [StartEngine method](https://msdn.microsoft.com/en-us/library/Ee418626(v=VS.85).aspx)
##### [StopEngine method](https://msdn.microsoft.com/en-us/library/Ee418628(v=VS.85).aspx)
##### [UnregisterForCallbacks method](https://msdn.microsoft.com/en-us/library/Ee418630(v=VS.85).aspx)
#### [IXAudio2Voice](/windows/desktop/api/xaudio2/nn-xaudio2-ixaudio2voice)
##### [DestroyVoice method](https://msdn.microsoft.com/en-us/library/Ee418481(v=VS.85).aspx)
##### [DisableEffect method](https://msdn.microsoft.com/en-us/library/Ee418583(v=VS.85).aspx)
##### [EnableEffect method](https://msdn.microsoft.com/en-us/library/Ee418584(v=VS.85).aspx)
##### [GetChannelVolumes method](https://msdn.microsoft.com/en-us/library/Ee418585(v=VS.85).aspx)
##### [GetEffectParameters method](https://msdn.microsoft.com/en-us/library/Ee418586(v=VS.85).aspx)
##### [GetEffectState method](https://msdn.microsoft.com/en-us/library/Ee418587(v=VS.85).aspx)
##### [GetFilterParameters method](https://msdn.microsoft.com/en-us/library/Ee418588(v=VS.85).aspx)
##### [GetOutputFilterParameters method](https://msdn.microsoft.com/en-us/library/Ee418589(v=VS.85).aspx)
##### [GetOutputMatrix method](https://msdn.microsoft.com/en-us/library/Ee418590(v=VS.85).aspx)
##### [GetVoiceDetails method](https://msdn.microsoft.com/en-us/library/Ee418591(v=VS.85).aspx)
##### [GetVolume method](https://msdn.microsoft.com/en-us/library/Ee418592(v=VS.85).aspx)
##### [SetChannelVolumes method](https://msdn.microsoft.com/en-us/library/Ee418593(v=VS.85).aspx)
##### [SetEffectChain method](https://msdn.microsoft.com/en-us/library/Ee418594(v=VS.85).aspx)
##### [SetEffectParameters method](https://msdn.microsoft.com/en-us/library/Ee418595(v=VS.85).aspx)
##### [SetFilterParameters method](https://msdn.microsoft.com/en-us/library/Ee418596(v=VS.85).aspx)
##### [SetOutputFilterParameters method](https://msdn.microsoft.com/en-us/library/Ee418597(v=VS.85).aspx)
##### [SetOutputMatrix method](https://msdn.microsoft.com/en-us/library/Ee418598(v=VS.85).aspx)
##### [SetOutputVoices method](https://msdn.microsoft.com/en-us/library/Ee418599(v=VS.85).aspx)
##### [SetVolume method](https://msdn.microsoft.com/en-us/library/Ee418600(v=VS.85).aspx)
#### [IXAudio2SourceVoice](/windows/desktop/api/xaudio2/nn-xaudio2-ixaudio2sourcevoice)
##### [Discontinuity method](https://msdn.microsoft.com/en-us/library/Ee418464(v=VS.85).aspx)
##### [ExitLoop method](https://msdn.microsoft.com/en-us/library/Ee418465(v=VS.85).aspx)
##### [FlushSourceBuffers method](https://msdn.microsoft.com/en-us/library/Ee418466(v=VS.85).aspx)
##### [GetFrequencyRatio method](https://msdn.microsoft.com/en-us/library/Ee418467(v=VS.85).aspx)
##### [GetState method](https://msdn.microsoft.com/en-us/library/Hh405047(v=VS.85).aspx)
##### [SetFrequencyRatio method](https://msdn.microsoft.com/en-us/library/Ee418469(v=VS.85).aspx)
##### [SetSourceSampleRate method](https://msdn.microsoft.com/en-us/library/Ee418470(v=VS.85).aspx)
##### [Start method](https://msdn.microsoft.com/en-us/library/Ee418471(v=VS.85).aspx)
##### [Stop method](https://msdn.microsoft.com/en-us/library/Ee418472(v=VS.85).aspx)
##### [SubmitSourceBuffer method](https://msdn.microsoft.com/en-us/library/Ee418473(v=VS.85).aspx)
#### [IXAudio2SubmixVoice](/windows/desktop/api/xaudio2/nn-xaudio2-ixaudio2submixvoice)
#### [IXAudio2MasteringVoice](/windows/desktop/api/xaudio2/nn-xaudio2-ixaudio2masteringvoice)
##### [GetChannelMask method](https://msdn.microsoft.com/en-us/library/Hh405046(v=VS.85).aspx)
#### [IXAudio2EngineCallback](/windows/desktop/api/xaudio2/nn-xaudio2-ixaudio2enginecallback)
##### [OnCriticalError method](https://msdn.microsoft.com/en-us/library/Ee418461(v=VS.85).aspx)
##### [OnProcessingPassEnd method](https://msdn.microsoft.com/en-us/library/Ee418462(v=VS.85).aspx)
##### [OnProcessingPassStart method](https://msdn.microsoft.com/en-us/library/Ee418463(v=VS.85).aspx)
#### [IXAudio2VoiceCallback](/windows/desktop/api/xaudio2/nn-xaudio2-ixaudio2voicecallback)
##### [OnBufferEnd method](https://msdn.microsoft.com/en-us/library/Ee418474(v=VS.85).aspx)
##### [OnBufferStart method](https://msdn.microsoft.com/en-us/library/Ee418475(v=VS.85).aspx)
##### [OnLoopEnd method](https://msdn.microsoft.com/en-us/library/Ee418476(v=VS.85).aspx)
##### [OnStreamEnd method](https://msdn.microsoft.com/en-us/library/Ee418477(v=VS.85).aspx)
##### [OnVoiceError method](https://msdn.microsoft.com/en-us/library/Ee418478(v=VS.85).aspx)
##### [OnVoiceProcessingPassEnd method](https://msdn.microsoft.com/en-us/library/Ee418479(v=VS.85).aspx)
##### [OnVoiceProcessingPassStart method](https://msdn.microsoft.com/en-us/library/Ee418480(v=VS.85).aspx)
#### [IXAPO](/windows/desktop/api/XAPO/nn-xapo-ixapo)
##### [CalcInputFrames method](https://msdn.microsoft.com/en-us/library/Ee418449(v=VS.85).aspx)
##### [CalcOutputFrames method](https://msdn.microsoft.com/en-us/library/Ee418450(v=VS.85).aspx)
##### [GetRegistrationProperties method](https://msdn.microsoft.com/en-us/library/Ee418451(v=VS.85).aspx)
##### [Initialize method](https://msdn.microsoft.com/en-us/library/Ee418452(v=VS.85).aspx)
##### [IsInputFormatSupported method](https://msdn.microsoft.com/en-us/library/Ee418453(v=VS.85).aspx)
##### [IsOutputFormatSupported method](https://msdn.microsoft.com/en-us/library/Ee418454(v=VS.85).aspx)
##### [LockForProcess method](https://msdn.microsoft.com/en-us/library/Ee418455(v=VS.85).aspx)
##### [Process method](https://msdn.microsoft.com/en-us/library/Ee418456(v=VS.85).aspx)
##### [Reset method](https://msdn.microsoft.com/en-us/library/Ee418459(v=VS.85).aspx)
##### [UnlockForProcess method](https://msdn.microsoft.com/en-us/library/Ee418460(v=VS.85).aspx)
#### [IXAPOParameters](/windows/desktop/api/XAPO/nn-xapo-ixapoparameters)
##### [GetParameters method](https://msdn.microsoft.com/en-us/library/Ee418443(v=VS.85).aspx)
##### [SetParameters method](https://msdn.microsoft.com/en-us/library/Ee418447(v=VS.85).aspx)
#### [IXAPOHrtfParameters](https://msdn.microsoft.com/en-us/library/Mt186608(v=VS.85).aspx)
##### [SetEnvironment method](https://msdn.microsoft.com/en-us/library/Mt186609(v=VS.85).aspx)
##### [SetSourceGain method](https://msdn.microsoft.com/en-us/library/Mt186610(v=VS.85).aspx)
##### [SetSourceOrientation method](https://msdn.microsoft.com/en-us/library/Mt186611(v=VS.85).aspx)
##### [SetSourcePosition method](https://msdn.microsoft.com/en-us/library/Mt186612(v=VS.85).aspx)
### [Macros](macros.md)
#### [XAPOAlloc](/windows/desktop/api/XAPO/nf-xapo-xapoalloc)
#### [XAPOFree](/windows/desktop/api/XAPO/nf-xapo-xapofree)
### [Structures](structures.md)
#### [HrtfApoInit](/windows/desktop/api/HrtfApoApi/ns-hrtfapoapi-hrtfapoinit)
#### [HrtfDirectivity](/windows/desktop/api/HrtfApoApi/ns-hrtfapoapi-hrtfdirectivity)
#### [HrtfDirectivityCardioid](/windows/desktop/api/HrtfApoApi/ns-hrtfapoapi-hrtfdirectivitycardioid)
#### [HrtfDirectivityCone](/windows/desktop/api/HrtfApoApi/ns-hrtfapoapi-hrtfdirectivitycone)
#### [HrtfDistanceDecay](/windows/desktop/api/HrtfApoApi/ns-hrtfapoapi-hrtfdistancedecay)
#### [HrtfOrientation](/windows/desktop/api/HrtfApoApi/ns-hrtfapoapi-hrtforientation)
#### [HrtfPosition](/windows/desktop/api/HrtfApoApi/ns-hrtfapoapi-hrtfposition)
#### [XAUDIO2_BUFFER](/windows/desktop/api/xaudio2/ns-xaudio2-xaudio2_buffer)
#### [XAUDIO2_BUFFER_WMA](/windows/desktop/api/xaudio2/ns-xaudio2-xaudio2_buffer_wma)
#### [XAUDIO2_DEBUG_CONFIGURATION](/windows/desktop/api/xaudio2/ns-xaudio2-xaudio2_debug_configuration)
#### [XAUDIO2_EFFECT_CHAIN](/windows/desktop/api/xaudio2/ns-xaudio2-xaudio2_effect_chain)
#### [XAUDIO2_EFFECT_DESCRIPTOR](/windows/desktop/api/xaudio2/ns-xaudio2-xaudio2_effect_descriptor)
#### [XAUDIO2_FILTER_PARAMETERS](/windows/desktop/api/xaudio2/ns-xaudio2-xaudio2_filter_parameters)
#### [XAUDIO2_PERFORMANCE_DATA](/windows/desktop/api/xaudio2/ns-xaudio2-xaudio2_performance_data)
#### [XAUDIO2_SEND_DESCRIPTOR](/windows/desktop/api/xaudio2/ns-xaudio2-xaudio2_send_descriptor)
#### [XAUDIO2_VOICE_DETAILS](/windows/desktop/api/xaudio2/ns-xaudio2-xaudio2_voice_details)
#### [XAUDIO2_VOICE_SENDS](/windows/desktop/api/xaudio2/ns-xaudio2-xaudio2_voice_sends)
#### [XAUDIO2_VOICE_STATE](/windows/desktop/api/xaudio2/ns-xaudio2-xaudio2_voice_state)
#### [XAUDIO2FX_REVERB_I3DL2_PARAMETERS](/windows/desktop/api/xaudio2fx/ns-xaudio2fx-xaudio2fx_reverb_i3dl2_parameters)
#### [XAUDIO2FX_REVERB_PARAMETERS](/windows/desktop/api/xaudio2fx/ns-xaudio2fx-xaudio2fx_reverb_parameters)
#### [XAUDIO2FX_VOLUMEMETER_LEVELS](/windows/desktop/api/xaudio2fx/ns-xaudio2fx-xaudio2fx_volumemeter_levels)
#### [XAPO_LOCKFORPROCESS_BUFFER_PARAMETERS](/windows/desktop/api/xapo/ns-xapo-xapo_lockforprocess_buffer_parameters)
#### [XAPO_PROCESS_BUFFER_PARAMETERS](/windows/desktop/api/xapo/ns-xapo-xapo_process_buffer_parameters)
#### [XAPO_REGISTRATION_PROPERTIES](/windows/desktop/api/xapo/ns-xapo-xapo_registration_properties)
#### [FXECHO_INITDATA](/windows/desktop/api/xapofx/ns-xapofx-fxecho_initdata)
#### [FXECHO_PARAMETERS](/windows/desktop/api/xapofx/ns-xapofx-fxecho_parameters)
#### [FXEQ_PARAMETERS](/windows/desktop/api/xapofx/ns-xapofx-fxeq_parameters)
#### [FXMASTERINGLIMITER_PARAMETERS](/windows/desktop/api/xapofx/ns-xapofx-fxmasteringlimiter_parameters)
#### [FXREVERB_PARAMETERS](/windows/desktop/api/xapofx/ns-xapofx-fxreverb_parameters)
#### [X3DAUDIO_CONE](/windows/desktop/api/x3daudio/ns-x3daudio-x3daudio_cone)
#### [X3DAUDIO_DISTANCE_CURVE](/windows/desktop/api/x3daudio/ns-x3daudio-x3daudio_distance_curve)
#### [X3DAUDIO_DISTANCE_CURVE_POINT](/windows/desktop/api/x3daudio/ns-x3daudio-x3daudio_distance_curve_point)
#### [X3DAUDIO_DSP_SETTINGS](/windows/desktop/api/x3daudio/ns-x3daudio-x3daudio_dsp_settings)
#### [X3DAUDIO_EMITTER](/windows/desktop/api/x3daudio/ns-x3daudio-x3daudio_emitter)
#### [X3DAUDIO_LISTENER](/windows/desktop/api/x3daudio/ns-x3daudio-x3daudio_listener)
