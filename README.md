[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/ldLXoPBi)

## Name
Carlos Gabriel Rodríguez Ornelas
## Link page
https://dsaw-2026-2.github.io/hw1-team-readme-and-project-kickoff-Gabo9702/

# HW01 — Team README & Project Kickoff

**Week 1 · DSAW · Universidad de La Sabana**

## Objective

Form your team, choose the problem you will solve this semester, and argue why it deserves a web application.

## Deliverables

Create the following files at the root of the repository:

### `README.md`
Must include:
- **Problem:** What problem are you solving? Be specific. Not "improve communication" but "Sabana students don't know when study rooms are available."
- **Web app justification:** Why a web app and not a spreadsheet, a WhatsApp group, or an existing tool? Give at least 3 concrete reasons.
- **Target users:** Who will use it? Be specific — not "anyone."
- **User stories (minimum 3):** Format: `As a [user type], I want to [action] so that [benefit].`
- **Team roles:** Who does what. Every team member must have a clear, named role.

### `index.html`
A simple landing page (no CSS yet) that introduces the project. GitHub Pages will publish it automatically.

### `figma-link.txt`
A text file containing the link to your Figma sketch (or a photo of a whiteboard). Any visual representation of how you imagine the app works.

## Layer 2

The sketch must show at least one screen with annotations that explain what each element does.

## AI Log

Did you use AI to write the user stories or the problem statement? If so, include in the README:
- The exact prompt you used
- What changed from what the AI generated
- Why you made those changes

## Deployment

The repository must have GitHub Pages enabled. The URL must load correctly.

## Autograding

The pipeline will check:
- ✅ Presence of `README.md`, `index.html`, `figma-link.txt`
- ✅ `index.html` has content
- ✅ `figma-link.txt` contains a URL
- ✅ GitHub Pages URL responds with HTTP 200
- ✅ README argues why a web app is the right solution (reviewed by Claude)

> **Submission rule:** If it is not deployed and public, it cannot be graded.

# MicroERP
## Problem

Las farmacias pequeñas e independientes administran sus ventas e inventarios mediante cuadernos o Excel, lo que provoca la pérdida de control exacto sobre las unidades disponibles, venta de productos caducados o errores en el registro de los empleados.

## Web app justification
- Acceso a multiplataforma: A diferencia de un software local, los vendedores y el administrador pueden acceder al sistema desde cualquier computadora o tableta sin instalar nada.
- Actualización automática del inventario: A diferencia de una libreta, el sistema descuenta automáticamente las unidades del inventario centralizado en el mismo instante en que se registra una venta.
- Control de usuarios y permisos: A diferencia de un archivo de Excel compartido, la web app permite restringir quién puede registrar medicamentos (administrador) y quién solo puede cobrar (vendedor).

## Target users
Propietarios, administradores y empleados encargados de la operación diaria de farmacias pequeñas e independientes (excluyendo grandes cadenas departamentales).

## User stories
- As an administrator, I want to register medications and their expiration dates so that I can control the inventory and avoid selling expired products.
- As an administrator, I want to register suppliers so that I know who provides each medication.
- As a seller, I want to search for medications by name or code so that I can quickly check their price and availability.
- As a seller, I want to register a sale so that the system automatically updates the inventory stock.
- As a guest, I want to browse the public catalog of the pharmacy so that I can know if the product I need is available.

## Team roles
- Jorge Luis Osorio Silva: Frontend y documentación
- Nicolás García Mejía: Infraestructura, Base de datos y backend
- Carlos Gabriel Rodríguez Ornelas: Backend y apoyo frontend

# AI Log
- Prompt used: Mejora la ortografía y redacción de la propuesta de nuestro proyecto MicroERP, y ajusta nuestras historias de usuario al formato estándar.
- What changed: La IA únicamente corrigió la redacción general del documento y adaptó las historias de usuario al formato en inglés.
- Why we made those changes: Para entregar un texto más claro y asegurar que las historias de usuario cumplieran exactamente con el formato requerido por la rúbrica.
