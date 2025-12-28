# Exercise Outcomes Submission Template

**Student/Group Name**: DS-02  
**Level Completed**: newbie  
**Date**: [29/12/2025]

---

## 📋 Exercise Summary

### Exercise: [Exercise Title]
**Status**: ✅ Completed

**What I did**:
Se clonó el repositorio público de los ejercicos localmente para poder realizar cambios. Se usó los comandos básicos de gestión de git para añadir, commit, log y hacer push y pull al remoto. Se modificó la plantilla OUTCOMES.md.

**Commands Used**:
```bash
# List the key Git commands you used across all parts of the exercise
git clone
git add
git commit
git checkout
git branch
git log
git push
git commit --amend
git push
git pull

```

**Results/Output**:
```
ver capturas abajo
```

**Screenshots** (if applicable):
- ![Screenshot](images/clone_checkout.jpg)
checkout newbie branch
- ![Screenshot](images/untracked.jpg)
Hola.txt no esta siendo seguido
- ![Screenshot](images/add.jpg)
Añadiendo Hola.txt
- ![Screenshot](images/status_tracked.jpg)
Estatus: Hola.txt está siendo seguido
- ![Screenshot](images/commit.jpg)
Commit de Hola.txt
- ![Screenshot](images/amend.jpg)
Cambio de usuario y correo y commit --amend
- ![Screenshot](images/log.jpg)
Log refleja el último commit
- ![Screenshot](images/new_status.jpg)
Estatus: OUTCOME.md modificada y my-info.txt sin seguimiento
- ![Screenshot](images/new_add_commit.jpg)
Añadir todo con git add . y commit
- ![Screenshot](images/push.jpg)
Push a la rama feature/my-info
- ![Screenshot](images/switch_pull_newbie.jpg)
checkout rama newbie y pull de últimos cambios

---

## 🎯 Key Learnings

**Main concepts I learned**:
1. Hacer fork de un repositorio
2. Clonar localmente
3. Gestionar usuario e email
4. stage y commit de nuevos archivos o cambios en archivos (tracking de nuevos archivos)
5. Mostrar logs para verificar cambios, p, ej. autor, email, fecha, etc.

**Skills I improved**:
- Discernir entre config local y config global para user.name y user.email (y otras configuraciones)
- Manejo de ramas locales y remotas
- Seguir archivos con git add y registrarlos con git commit
- Actualizar rama local con git pull y guardar en rama remota con git push
---

## 🚧 Challenges Faced

### Challenge 1: [Brief title]
**Problem**: Olvidé cambiar user.name y user.email correcto (tengo varios usuarios y cuentas).

**Solution**:  Hice un git commit --amend para modificar el último commit.

**Commands/Approach**:
- git config user.name "myusername"
- git config user.email "myemail"
- git commit --amend --reset-author

---

## 💭 Personal Reflection

**What surprised me**:
[What unexpected things did you discover about Git?]
Hay diferentes niveles de configuracion: local, global, system. Puede resultar confuso si no se sabe la precedencia de las configuraciones.

**What I found most difficult**:
[Which concepts or exercises were most challenging?]
No fue un ejercicio especialmente difícil. Lo que más demandó fue buscar la manera de cambiar de usuario.

**What I found most useful**:
[Which skills do you think will be most valuable in real projects?]
Mantener un repositorio remoto (usando clone, push y pull) para poder compartir y colaborar con otras personas en un mismo proyecto.

**How I would apply this in real projects**:
[Describe how you might use these Git skills in professional work]
Por ejemplo, para distribuir el trabajo entre colaboradores que modifican distintas ramas y trabajan en diferentes funcionalidades de un proyecto.

---

## 📊 Self-Assessment

Rate your confidence level for each topic (1-5, where 5 is very confident):

| Topic | Confidence (1-5) | Notes |
|-------|------------------|-------|
| Basic Git commands | [5 ] | |
| Branching & merging | [4 ] | |
| Remote operations | [4 ] | |
| Conflict resolution | [2 ] | |
| History rewriting | [3 ] | |
| Git hooks | [1 ] | |
| Security practices | [2 ] | |

---

## 🔗 Evidence/Artifacts

**Links to branches/commits**:
- Link to your outcome branch: `https://github.com/ejdsaatorres-tech/taller-master-ugr/tree/group-DS-02-outcomes/newbie`
- Key commits demonstrating your work:
  - Commit hash: fff7acdca8d543deae681cfc2499cf460e7dc705 [Añadir Hola.txt]
  - Commit hash: 216dff4f5578207159a70e076c18688bed346cf2 [Añadir OUTCOMES.md]
  - Commit hash: 4c6a0bb7d3c9f888355624db303bdc59ecb549a8 [Añadir personal_info.txt]
  - Commit hash: a707b0f737ede05754e81da1b3d18117966330ea [Creacion de rama feature/my-info]
  - Commit hash: 80c3a036236de9adf4d98cfc46d4a2b6aeff59bc [Creacion de rama group-DS-02-outcomes/newbie]
  - Commit hash:

**Additional files created** (if any):
- Hola.txt
- my-info.txt

---

## ✅ Completion Checklist

Before submitting, ensure you have:
- [✅] Completed the exercise for your chosen level (including all parts)
- [✅] Documented all commands used with their outputs
- [✅] Described challenges and how you resolved them
- [✅] Provided a thoughtful reflection on your learning
- [✅] Self-assessed your confidence in each topic
- [✅] Pushed your outcome branch to the remote repository
- [✅] Created a Pull Request (if required by your instructor)

---

## 📝 Additional Comments

---

**Submission Date**: [29/12/2025]  
**Ready for Review**: ✅ Yes