# Medical Platform

Celem pracy jest zaprojektowanie oraz implementacja systemu informatycznego do zarządzania wizytami lekarskimi oraz zaleceniami medycznymi. Uwaga zostanie położona na potrzeby róż-nych grup użytkowników, ze szczególnym wyróżnieniem grupy seniorów. Zadaniem systemu jest zapewnienie wygodnego dostępu do informacji o procesie leczenia oraz usprawnienie ko-munikacji między jego uczestnikami.
Zaprojektowane zostało rozwiązanie, które opiera się na architekturze klient-serwer i składa się z aplikacji mobilnej, webowej oraz wspólnego backendu. Przy tym, istotnym założeniem było, aby system był czytelny oraz łatwy w obsłudze dla osób starszych, ale nie tracił przez to funk-cjonalności dla innych użytkowników.

## Stack Technologiczny

### Frontend

#### Aplikacja webowa
- Next.js
- React
- TypeScript
- Tailwind CSS

#### Aplikacja mobilna
- React Native
- Expo
- TypeScript

### Backend

- NestJS
- Node.js
- REST API
- JWT
- bcrypt

### Warstwa danych

- PostgreSQL
- Prisma ORM

### Infrastruktura i Deployment

- Docker
- Kubernetes (AKS)
- Helm

### CI/CD i DevOps

- Azure DevOps – CI/CD pipelines
- Azure Container Registry
- Terraform – infrastructure as code

# Spis treści

1. Wstęp\
   1.1. Cel pracy\
   1.2. Zakres pracy
2. Analiza problemu i przegląd istniejących rozwiązań\
   2.1. Charakterystyka systemów medycznych dla pacjentów\
   2.2. Specyfikacja potrzeb seniorów w systemach IT\
   2.3. Przegląd istniejących aplikacji do umawiania wizyt\
   2.4. Założenia projektowanego systemu
3. Wymagania systemowe\
   3.1. Wymagania funkcjonalne\
   3.2. Wymagania niefunkcjonalne\
   3.3. Role użytkownika systemu.\
   3.4. Przypadki użycia systemu
4. Projekt architektury systemu\
   4.1. Założenia architektoniczne\
   4.2. Model architektury systemu\
   4.3. Architektura warstwy prezentacji\
   4.4. Architektura backendu\
   4.5. Projekt bazy danych\
   4.6. Komunikacja między komponentami\
   4.7. Mechanizmy bezpieczeństwa\
   4.8 Wdrożenie systemu i środowisko uruchomieniowe
5. Implementacja\
   5.1. Środowisko programistyczne\
   5.2. Implementacja backendu\
   5.3. Implementacja aplikacji webowej\
   5.4. Implementacja aplikacji mobilnej\
   5.5. Implementacja bazy danych\
   5.6. Integracja komponentów systemu\
   5.7. Proces budowy i wdrożenia systemu
6. Podsumowanie\
   6.1. Podsumowanie pracy\
   6.2. Możliwość dalszego rozwoju\
   6.3. Wnioski końcowe
