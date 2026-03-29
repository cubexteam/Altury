<h1 align="center">⚡ Altury</h1>
<p align="center">Мощное серверное ядро для Minecraft Bedrock Edition</p>
<p align="center">
  <img src="https://img.shields.io/badge/Minecraft-1.20--1.26-brightgreen" alt="Minecraft versions"/>
  <img src="https://img.shields.io/badge/Java-21+-orange" alt="Java 21+"/>
  <img src="https://img.shields.io/badge/Platform-Bedrock-blue" alt="Bedrock"/>
</p>

---

## О проекте

Altury — серверное программное обеспечение для Minecraft Bedrock Edition, созданное для производительности, стабильности и расширенных возможностей API.

## Возможности

- Поддержка Minecraft Bedrock **1.20.0 – 1.26.10** (минимальный протокол настраивается)
- Поддержка кастомных блоков и кастомных зачарований
- Улучшенная система AntiXray
- Расширенное API (эффекты, еда и многое другое)
- Улучшенное соответствие ванильному поведению

## Запуск

1. Установи **Java 21** или выше (рекомендуется Azul Zulu 21)
2. Скачай последний `.jar` из [Releases](https://github.com/cubexteam/Altury/releases)
3. Запусти: `java -jar Altury-1.0.0.jar`

## Maven

```xml
<repositories>
    <repository>
        <id>altury-releases</id>
        <url>https://repo.cubexteam.dev/releases</url>
    </repository>
</repositories>

<dependency>
    <groupId>dev.santiandev</groupId>
    <artifactId>Altury</artifactId>
    <version>1.0.0</version>
</dependency>
```

## Gradle

```kts
maven {
    name = "alturyReleases"
    url = uri("https://repo.cubexteam.dev/releases")
}
```

```kts
compileOnly("dev.santiandev:Altury:1.0.0")
```

## Авторы

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/cubexteam">
        <img src="https://github.com/cubexteam.png" width="80px" style="border-radius:50%" alt="SantianDev"/>
        <br/>
        <sub><b>SantianDev</b></sub>
      </a>
      <br/>
      <img src="https://img.shields.io/badge/-Автор-2ea44f?style=flat-square" alt="Автор"/>
    </td>
    <td align="center">
      <a href="https://github.com/ka1larness">
        <img src="https://github.com/ka1larness.png" width="80px" style="border-radius:50%" alt="bota"/>
        <br/>
        <sub><b>bota</b></sub>
      </a>
      <br/>
      <img src="https://img.shields.io/badge/-Автор-2ea44f?style=flat-square" alt="Автор"/>
    </td>
  </tr>
</table>

## Создано с помощью

[<img src="https://raw.githubusercontent.com/CloudburstMC/Nukkit/master/.github/images/logo.png" width="18"/>]() [Nukkit](https://github.com/CloudburstMC/Nukkit)  
[<img src="https://avatars.githubusercontent.com/u/62042238?s=200&v=4" width="18"/>]() [Nukkit-MOT](https://github.com/MemoriesOfTime/Nukkit-MOT)  
[<img src="https://github.com/KoshakMineDEV.png" width="18"/>]() [Lumi by KoshakMineDEV](https://github.com/KoshakMineDEV/Lumi)