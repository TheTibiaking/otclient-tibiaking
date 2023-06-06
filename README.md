# Projeto OTClient TibiaKing

<center>
<a href="https://www.tibiaking.com"><img src="https://user-images.githubusercontent.com/74227915/219124653-caccb04f-e858-4e81-b8be-c94ffbd3f276.png"/></a>
</center>

## Build Status

[![Build - Windows](https://github.com/TheTibiaking/otclient-tibiaking/actions/workflows/build-windows.yml/badge.svg?branch=master)](https://github.com/TheTibiaking/otclient-tibiaking/actions/workflows/build-windows.yml)
[![Build - Ubuntu](https://github.com/TheTibiaking/otclient-tibiaking/actions/workflows/ubuntu-build.yml/badge.svg)](https://github.com/TheTibiaking/otclient-tibiaking/actions/workflows/ubuntu-build.yml)
[![Build - Docker](https://github.com/TheTibiaking/otclient-tibiaking/actions/workflows/docker-build.yml/badge.svg)](https://github.com/TheTibiaking/otclient-tibiaking/actions/workflows/docker-build.yml)

Este é um cliente baseado no [OTClient](https://github.com/edubart/otclient) desenvolvido por [Edubart](https://github.com/edubart/) e editado por [Mehah](https://github.com/mehah/) e pela comunidade. Esta fork é baseada na revisão [e81900547cd224b6d2c98550f360f78b49575285](https://github.com/mehah/otclient/tree/e81900547cd224b6d2c98550f360f78b49575285).

## Sobre o Projeto

O OTClient TibiaKing é uma versão personalizada do OTClient que foi projetada para ser altamente estável e é amplamente utilizada pela maioria dos servidores privados de Tibia. Ele foi desenvolvido com o objetivo de funcionar perfeitamente com a maioria das versões do [TFS (The Forgotten Server)](https://github.com/tibiaking/forgottenserver).

Este repositório é uma ferramenta valiosa para o desenvolvimento de sistemas, correção de bugs e configurações personalizadas em servidores privados de Tibia.

## Funcionalidades do OTClient TibiaKing

- C++20
- Sistema de renderização refatorado
- Novo sistema de iluminação
- Recarregamento automático para módulos (necessário ativar em init.lua)
- Sistema de efeitos diretamente na posição do personagem (aura, asas) (Exemplos: effects.lua, outfit_618.lua, código de teste)
- Animação para personagens parados
- Destaque visível onde o mouse passa (Highlight)
- Novo sistema de crosshair
- Sombras nos pisos
- Visão dos pisos (fade, fadein, walkfade...)
- Novas opções de antialiasing
- Possibilidade de criar efeitos flutuantes no personagem
- Melhoria no sistema de andar no minimapa
- Terminal aprimorado
- Walk system refatorado
- Suporte a mais botões do mouse (Mouse4, Mouse5, etc)
- Sistema de controle de módulo (Exemplo de código)
- Configuração do cliente em Config config.h
- Suporte para versões do Tibia 12.85 a 12.92 (protobuf)
- Sistema de mercado funcional com Canary
- Suporte ao Tibia 12.85
- Suporte ao Discord RPC
- Fade nos pisos
- Action Bar
- Acesso aos elementos filhos do widget via widget.childId
- Correção no sistema de shaders (CTRL + Y)
- Módulo de batalha refatorado
- Círculo de vida e mana
- Tema do Tibia 1.2

## Como Buildar e Executar com Docker

Em breve...

## Download

[Windows Builds](https://github.com/TheTibiaking/otclient-tibiaking/releases)

## Wiki

[OTC-TK](https://github.com/TheTibiaking/otclient-tibiaking/wiki)

### Créditos

Este projeto foi possível graças aos esforços de Edubart, Mehah e à equipe do TibiaKing. 
Agradecemos a todos os desenvolvedores e colaboradores envolvidos na criação do OTClient TibiaKing e por contribuírem para uma comunidade de servidores privados de Tibia ativa e vibrante.

---
