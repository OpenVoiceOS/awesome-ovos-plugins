# awesome-ovos-plugins
List of ovos-plugin-manager plugins and projects

This is a list of Assistant plugins distributed by the OpenVoiceOS team. Most of them are also developed by OVOS. 
OPM plugins are always usable outside of Mycroft, in any Python project. All should be compatible with any Mycroft-based Assistant.

NOTE: This awesomelist is curated for OVOS-derived software.

Plugins written against mycroft-core should be listed in [awesome-mycroft-community](https://github.com/ChanceNCounter/awesome-mycroft-community)

## OPM plugins

### STT

##### Local
- [ovos-stt-plugin-vosk](https://github.com/OpenVoiceOS/ovos-stt-plugin-vosk)
- [neon-stt-plugin-scribosermo](https://github.com/NeonGeckoCom/neon-stt-plugin-scribosermo)
- [neon-stt-plugin-deepspeech_stream_local](https://github.com/NeonGeckoCom/neon-stt-plugin-deepspeech_stream_local)
- [ovos-stt-plugin-pocketsphinx](https://github.com/OpenVoiceOS/ovos-stt-plugin-pocketsphinx)

##### Hosted
- [ovos-stt-plugin-chromium](https://github.com/OpenVoiceOS/ovos-stt-plugin-chromium)
- [neon-stt-plugin-google_cloud_streaming](https://github.com/NeonGeckoCom/neon-stt-plugin-google_cloud_streaming)


### TTS

##### Local
- [ovos-tts-plugin-mimic](https://github.com/OpenVoiceOS/ovos-tts-plugin-mimic)
- [ovos-tts-plugin-pico](https://github.com/OpenVoiceOS/ovos-tts-plugin-pico)
- [ovos-tts-plugin-espeakNG](https://github.com/OpenVoiceOS/ovos-tts-plugin-espeakNG)
- [ovos-tts-plugin-voicerss](https://github.com/OpenVoiceOS/ovos-tts-plugin-voicerss)
- [ovos-tts-plugin-SAM](https://github.com/OpenVoiceOS/ovos-tts-plugin-SAM)
- [ovos-tts-plugin-cotovia](https://github.com/OpenVoiceOS/ovos-tts-plugin-cotovia)
- [neon-tts-plugin-mozilla_local](https://github.com/NeonGeckoCom/neon-tts-plugin-mozilla_local)

##### Hosted
- [ovos-tts-plugin-mimic2](https://github.com/OpenVoiceOS/ovos-tts-plugin-mimic2)
- [ovos-tts-plugin-google-TX](https://github.com/OpenVoiceOS/ovos-tts-plugin-google-TX)
- [ovos-tts-plugin-responsivevoice](https://github.com/OpenVoiceOS/ovos-tts-plugin-responsivevoice)
- [ovos-tts-plugin-catotron](https://github.com/OpenVoiceOS/ovos-tts-plugin-catotron)
- [ovos-tts-plugin-softcatala](https://github.com/OpenVoiceOS/ovos-tts-plugin-softcatala)
- [chatterbox-polly-tts-plugin](https://pypi.org/project/chatterbox-plugin-polly-tts)
- [neon-tts-plugin-mozilla_remote](https://github.com/NeonGeckoCom/neon-tts-plugin-mozilla_remote)
- [neon-tts-plugin-polly](https://github.com/NeonGeckoCom/neon-tts-plugin-polly)
- [neon-tts-plugin-larynx_server](https://github.com/NeonGeckoCom/neon-tts-plugin-larynx_server)

### WakeWord

##### Local
- [ovos-ww-plugin-hotkeys](https://github.com/OpenVoiceOS/ovos_ww_plugin_hotkeys)
- [ovos-ww-plugin-pocketsphinx](https://github.com/OpenVoiceOS/ovos-ww-plugin-pocketsphinx)
- [ovos-ww-plugin-snowboy](https://github.com/OpenVoiceOS/ovos-ww-plugin-snowboy)
- [ovos-ww-plugin-vosk](https://github.com/OpenVoiceOS/ovos-ww-plugin-vosk)
- [ovos-ww-plugin-precise](https://github.com/OpenVoiceOS/ovos-ww-plugin-precise)
- [ovos-ww-plugin-precise-lite](https://github.com/OpenVoiceOS/ovos-ww-plugin-precise-lite)
- [ovos-ww-plugin-nyumaya](https://github.com/OpenVoiceOS/ovos-ww-plugin-nyumaya)
- [ovos-ww-plugin-nyumaya-legacy](https://github.com/OpenVoiceOS/ovos-ww-plugin-nyumaya-legacy)
- [mycroft-porcupine-plugin](https://github.com/forslund/mycroft-porcupine-plugin)
- [chatterbox-ww-plugin-dummy](https://github.com/HelloChatterbox/dummy_wakeword_plugin)
- [neon_ww_plugin_efficientwordnet](https://github.com/NeonGeckoCom/neon_ww_plugin_efnet)

### AudioService

##### Local
- [ovos-ocp-audio-plugin](https://github.com/OpenVoiceOS/ovos-ocp-audio-plugin)
- [ovos-vlc-plugin](https://github.com/OpenVoiceOS/ovos-vlc-plugin)

### Language Detection / Translation

##### Local
- [neon-lang-plugin-cld2](https://github.com/NeonGeckoCom/neon-lang-plugin-cld2)
- [neon-lang-plugin-cld3](https://github.com/NeonGeckoCom/neon-lang-plugin-cld3)
- [neon-lang-plugin-langdetect](https://github.com/NeonGeckoCom/neon-lang-plugin-langdetect)
- [neon-lang-plugin-fastlang](https://github.com/NeonGeckoCom/neon-lang-plugin-fastlang)
- [neon-lang-plugin-lingua_podre](https://github.com/NeonGeckoCom/neon-lang-plugin-lingua_podre)

##### Hosted
- [neon-lang-plugin-google_translate](https://github.com/NeonGeckoCom/neon-lang-plugin-google_translate)
- [neon-lang-plugin-libretranslate](https://github.com/NeonGeckoCom/neon-lang-plugin-libretranslate)
- [neon-lang-plugin-amazon_translate](https://github.com/NeonGeckoCom/neon-lang-plugin-amazon_translate)
- [neon-lang-plugin-apertium](https://github.com/NeonGeckoCom/neon-lang-plugin-apertium)



### Utterance Transformers

##### Local
- [neon_utterance_cancel_plugin](https://github.com/NeonGeckoCom/neon_utterance_cancel_plugin) - pre-intent action
- [neon_utterance_translator_plugin](https://github.com/NeonGeckoCom/neon_utterance_translator_plugin) - pre-intent action
- [neon_utterance_normalizer_plugin](https://github.com/NeonGeckoCom/neon_utterance_normalizer_plugin) - pre-intent action
- [neon_utterance_pronomial_plugin](neon_utterance_pronomial_plugin) - pre-intent action (coreference resolution)
- [neon_utterance_RAKE_plugin](https://github.com/NeonGeckoCom/neon_utterance_RAKE_plugin) - inject context (keyword extraction)
- [neon_utterance_YAKE_plugin](https://github.com/NeonGeckoCom/neon_utterance_YAKE_plugin) - inject context (keyword extraction)
- [neon_utterance_KeyBERT_plugin](https://github.com/NeonGeckoCom/neon_utterance_KeyBERT_plugin) - inject context (keyword extraction)
- [neon_utterance_postag_plugin](https://github.com/NeonGeckoCom/neon_utterance_postag_plugin) - inject context (postag)
- [neon_utterance_simpleNER_plugin](https://github.com/NeonGeckoCom/neon_utterance_simpleNER_plugin) - inject context (NER)
- [neon_utterance_zeroshot_ner_plugin](https://github.com/NeonGeckoCom/neon_utterance_zeroshot_ner_plugin) - inject context (NER)
- [neon_utterance_zeroshot_topics_plugin](https://github.com/NeonGeckoCom/neon_utterance_zeroshot_topics_plugin) - inject context
- [neon_utterance_littlequestions_plugin_plugin](https://github.com/NeonGeckoCom/neon_utterance_littlequestions_plugin) - inject context
- [neon_utterance_zeroshot_clf_plugin](https://github.com/NeonGeckoCom/neon_utterance_zeroshot_clf_plugin) - inject context
- [neon_utterance_wn_entailment_plugin](https://github.com/NeonGeckoCom/neon_utterance_wn_entailment_plugin) - inject context 


##### Hosted
- [neon_utterance_neuralcorefdemo_plugin](https://github.com/NeonGeckoCom/neon_utterance_neuralcorefdemo_plugin) - pre-intent action (coreference resolution)


### Audio Transformers

##### Local
- [neon_noise_level_plugin](https://github.com/NeonGeckoCom/neon_noise_level_plugin) - event emitter
- [neon_audio_normalizer_plugin](https://github.com/NeonGeckoCom/neon_audio_normalizer_plugin) - pre-STT action

## Projects using OPM

- [OpenVoiceOS](https://github.com/OpenVoiceOS/OpenVoiceOS) - OVOS [onboarding](https://github.com/OpenVoiceOS/skill-ovos-setup) options are mimic, mimic2, pico, larynx, vosk, google
- [ovos-core](https://github.com/OpenVoiceOS/ovos-core) - OPM was essentially extracted from this codebase to make plugins standalone
- [neon-core](https://github.com/NeonGeckoCom/NeonCore) - 
- [ovos-local-backend](https://github.com/OpenVoiceOS/ovos-local-backend) - permissevely licensed alternative to the official mycroft backend
- [HiveMind voice satellite](https://github.com/JarbasHiveMind/HiveMind-voice-sat)
