# Plan audytu — nocodb

## Status
AUDYT ZAKOŃCZONY — 2026-09-12.

## Ustalenia
Duży upstreamowy no-code database/app platform. Złożona warstwa API, UI, pluginów i integracji danych.

## Ryzyka
RBAC, multi-tenant data isolation, API tokens, import/export, plugin execution, SSRF i dostęp do datasource.

## Dalsza praca
Traktować jako upstream/reference. Własne wdrożenie wymaga security review uprawnień, sekretów, datasource connectors i izolacji pluginów.
