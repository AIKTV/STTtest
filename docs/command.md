### live 普通话 cuda largeV3

```shell
whisper-ctranslate2 --live_transcribe True --language Mandarin --device cuda --model_directory ../model/faster-whisper-large-v3
```

### live 英语 cuda largeV3

```shell
whisper-ctranslate2 --live_transcribe True --language English --device cuda --model_directory ../model/faster-whisper-large-v3
```

### 转录 普通话 cuda largeV3 颜色置信度

```shell
whisper-ctranslate2 ../test/测试.mp3 --language Mandarin --device cuda --model_directory ../model/faster-whisper-large-v3 --print_colors True --output_dir ../output
```

### 转录 英语 cuda largeV3 颜色置信度

```shell
whisper-ctranslate2 ../test/第三篇.aac --language English --device cuda --model_directory ../model/faster-whisper-large-v3 --print_colors True --output_dir ../output
```

### 翻译 普通话 cuda largeV3 颜色置信度

```shell
whisper-ctranslate2 ../test/6.mp3 --language Mandarin --device cuda --model_directory ../model/faster-whisper-large-v3 --print_colors True --output_dir ../output --task translate
```

### 翻译 英语 cuda largeV3 颜色置信度

```shell
whisper-ctranslate2 ../test/6.mp3 --language English --device cuda --model_directory ../model/faster-whisper-large-v3 --print_colors True --output_dir ../output --task translate
```