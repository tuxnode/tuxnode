<!-- Header 动态打字机效果 -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1000&color=57A143&center=true&vCenter=true&width=700&lines=Executing+at+0x80000000...;Systems+Programming+Enthusiast;Breaking+binaries%2C+securing+stacks.;Living+in+Neovim+%2F+Tmux;" alt="Typing SVG" />
</p>

---

<!-- 主体内容布局 -->
<table align="center" width="100%" style="border-collapse: collapse; border: none;">
  <tr style="border: none;">
    <!-- 左栏：个人简介 -->
    <td valign="top" width="55%" style="border: none; padding-right: 10px;">
      <h3>⚙️ System Status</h3>
      <p>An undergraduate enthusiast deep-diving into low-level systems and binary safety.</p>
      <ul>
        <li>🔬 Hacking <b>xv6</b> kernel & building <b>RISC-V (NEMU)</b> simulator.</li>
        <li>🛡️ Exploiting stacks, heaps, and breaking binaries in CTFs.</li>
        <li>🚀 Crafting efficient network utilities in <b>Go</b>.</li>
        <li>🎨 Configuring compiler-ready pipelines inside <b>AstroNvim</b>.</li>
      </ul>
    </td>
    <!-- 右栏：技术栈胶囊徽章（使用更内敛的 flat-square 样式） -->
    <td valign="top" width="45%" style="border: none; padding-left: 10px;">
      <h3>🛠️ Core Matrix</h3>
      <p>
        <img src="https://img.shields.io/badge/C-%23A8B9CC.svg?style=flat-square&logo=c&logoColor=black" />
        <img src="https://img.shields.io/badge/Go-%2300ADD8.svg?style=flat-square&logo=go&logoColor=white" />
        <img src="https://img.shields.io/badge/Python-%233776AB.svg?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/RISC--V-%23F15A24.svg?style=flat-square&logo=riscv&logoColor=white" />
      </p>
      <p>
        <img src="https://img.shields.io/badge/Neovim-%2357A143.svg?style=flat-square&logo=neovim&logoColor=white" />
        <img src="https://img.shields.io/badge/Docker-%232496ED.svg?style=flat-square&logo=docker&logoColor=white" />
        <img src="https://img.shields.io/badge/Linux-%23FCC624.svg?style=flat-square&logo=linux&logoColor=black" />
        <img src="https://img.shields.io/badge/Git-%23F05032.svg?style=flat-square&logo=git&logoColor=white" />
      </p>
    </td>
  </tr>
</table>

---

<!-- 核心指令对齐彩蛋 -->
```c
#include <stdint.h>

void boot_sequence(void) {
    uint64_t pc = 0x80000000;
    
    // Strict adherence to the RISC-V specification
    pc = (pc + 4) & ~1ULL; 
    
    /* System initialized successfully. */
}
