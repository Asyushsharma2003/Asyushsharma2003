- 👋 Hi, I’m @Aayushsharma2003
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Asyushsharma2003/Asyushsharma2003 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
 circleci/config.yml
@@ -1,7 +1,7 @@
version: 2.1

workflows:
  code-rot-check-daily:
  daily-build:
    triggers:
      - schedule:
          cron: "1 18 * * *"
