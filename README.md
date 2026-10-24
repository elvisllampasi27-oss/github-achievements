# \# 🏆 Guía de insignias de GitHub (en español)

# 

# Guía práctica para conseguir los logros (achievements) que aparecen en tu perfil de GitHub. Todo lo explicado aquí fue probado paso a paso.

# 

# \## Insignias disponibles

# 

# | Insignia | Cómo se obtiene | Niveles |

# |---|---|---|

# | 🤠 Quickdraw | Cerrar un issue o PR menos de 5 minutos después de abrirlo | Único |

# | 🦈 Pull Shark | Que te fusionen Pull Requests | 2 · 16 · 128 · 1024 |

# | 🎲 YOLO | Fusionar un PR sin esperar la revisión que pediste | Único |

# | 👥 Pair Extraordinaire | Ser coautor de un commit en un PR fusionado | 1 · 10 · 24 · 48 |

# | 🧠 Galaxy Brain | Respuestas aceptadas en Discussions de un repositorio | 2 · 8 · 16 · 32 |

# | ⭐ Starstruck | Que un repositorio tuyo reciba estrellas | 16 · 128 · 512 · 4096 |

# | 💖 Public Sponsor | Patrocinar a alguien con GitHub Sponsors | Único |

# 

# \## Antes de empezar

# 

# Configura tu identidad con el \*\*mismo correo de tu cuenta de GitHub\*\*, o tus commits no contarán:

# 

# ```cmd

# git config --local user.name "TuUsuario"

# git config --local user.email "tu-correo@ejemplo.com"

# ```

# 

# Si usas una computadora compartida, usa `--local` y al terminar borra tu sesión en el Administrador de credenciales de Windows (entrada `git:https://github.com`).

# 

# \## 🤠 Quickdraw

# 

# 1\. Crea un issue en cualquier repositorio tuyo.

# 2\. Ciérralo antes de 5 minutos.

# 

# \## 🦈 Pull Shark

# 

# ```cmd

# git checkout -b docs/mi-cambio

# git add .

# git commit -m "docs: describir el cambio"

# git push -u origin docs/mi-cambio

# ```

# 

# Abre el enlace que muestra la terminal, crea el Pull Request y fusiónalo. Repite con cambios útiles.

# 

# \## 👥 Pair Extraordinaire

# 

# Agrega a la persona con quien trabajaste como coautora. Su correo lo puedes ver con:

# 

# ```cmd

# git log --format="%an <%ae>" | sort /unique

# ```

# 

# Luego haz el commit con dos `-m`:

# 

# ```cmd

# git commit -m "docs: mejorar guía" -m "Co-authored-by: Nombre <correo@users.noreply.github.com>"

# ```

# 

# Al fusionar con \*\*Squash and merge\*\*, verifica que la línea `Co-authored-by` siga en el mensaje final.

# 

# \## 🎲 YOLO

# 

# 1\. Agrega a un compañero como colaborador del repositorio.

# 2\. Abre un PR y pídele revisión en \*\*Reviewers\*\*.

# 3\. Fusiónalo sin esperar su aprobación.

# 

# \## 🧠 Galaxy Brain

# 

# 1\. Activa Discussions: Settings → General → Features → Discussions.

# 2\. Un compañero crea una pregunta en la categoría \*\*Q\&A\*\*.

# 3\. Tú la respondes y él la marca con \*\*Mark as answer\*\*.

# 4\. Repite una vez más.

# 

# Solo cuentan las discusiones de repositorios, no las del foro GitHub Community.

# 

# \## ⭐ Starstruck

# 

# Comparte proyectos útiles. Las estrellas que te das a ti mismo no cuentan.

# 

# \---

# 

# ¿Te sirvió? Dale una ⭐ al repositorio para que más personas lo encuentren.

