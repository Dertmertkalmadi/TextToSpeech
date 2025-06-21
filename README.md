# TextToSpeech

from text_to_speech import save

text = " bu alanda ne konuşturmak istiyorsanız veya metniniz ne ise onu yapıştırabilirsiniz."
language = "tr"  # Specify the language (IETF language tag)
output_file = "hello_world.mp3"  # Specify the output file (only accepts .mp3)

save(text, language, file=output_file)
