# Trabajo de Fin de Máster

# Síntesis de voz con aprendizaje profundo: análisis de modelos de text-to-speech y de voice conversion

## Autor: Jorge Alpuente Requena

## Tutores: 
## Emilio Soria Olivas
## Ángel Guevera Ros


En este repositorio se encuentran el código y los audios del trabajo. 

Por cuestiones de espacio, no se incluyen todos los audios empleados, sino uno por locutor y modelo a modo de muestra.

En el experimento 1, se incluye un audio real de cada locutor (carpeta audio) y un audio sintetizado de cada modelo TTS con la voz de cada locutor (synthesized audios).

En el experimento 2, se incluye un audio real de cada locutor (carpeta OriginalAudios) y, para cada uno de esos audios reales, la voz se convierte a la del resto de locutores sin alterar el contenido lingüístico (carpeta ClonedAudiosOut). Por ejemplo, para el audio del locutor con id=speaker_a (Experiment2\OriginalAudios\speaker_a\audio_id.wav) se sustituye la voz de otro locutor con id=speaker_b (Experiment2\ClonedAudiosout\speaker_b\speaker_a\audio_id.out.wav).