## Hi, I'm @debug-null 👋
 
   ![状态](https://img.shields.io/badge/状态-debug%20中-orange?style=flat-square)
   ![心情](https://img.shields.io/badge/心情-null-lightgrey?style=flat-square)
   ![咖啡存量](https://img.shields.io/badge/咖啡存量-不足-red?style=flat-square)
 
   > debug 了一整晚，最后发现 null 是我自己赋的。
 
   ```ts
   class Me extends NullPointerException {
     擅长 = ["写 bug", "复现不了的 bug", "在我电脑上能跑"];
     正在学 = "怎么把 bug 写成 feature";
     求合作 = "一起背锅的那种";
 
     daily() {
       try {
         coffee();
         work();
       } catch (e: ProductionIncident) {
         panic();
         git.push({ force: true }); // 🔥
       } finally {
         return null;
       }
     }
   }
   ```
 
   - 👀 对「这段代码昨晚明明能跑」这一世界未解之谜充满好奇
   - 🌱 正在深入学习《Stack Overflow 复制粘贴工程学》
   - 💞️ 寻求合作：需求是模糊的，deadline 是明天的，锅是一起背的
   - 📫 联系我：在 issue 里 `throw new Error("hello")`，我会 `catch` 到你
 
   ---
 
   `console.log("都看到这儿了，奖励你一个 🐛")`
