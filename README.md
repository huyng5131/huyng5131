<div align="center">
  <img src="https://media.gifdb.com/capoo-cat-typing-on-desk-gh8k0cjf5hq4vy2p.gif" width="220" />
</div>

```verilog
module nguyen_gia_huy (
    input  wire clk,
    input  wire rst_n,
    output wire [63:0] core_skills,
    output reg  [31:0] current_focus
);

    // Computer Engineering Undergrad @ UIT - VNUHCM
    // Base of Operations: Ho Chi Minh City, Vietnam

    assign core_skills = {RTL_Design, RISC_V, VLSI, Embedded_C};

    always @(posedge clk or negedge rst_n) begin
        if (!rst_n) begin
            current_focus <= 32'h0;
        end else begin
            // Building foundational skills step-by-step
            current_focus <= {MultiCore_Systems, AXI4_Bus};
        end
    end

endmodule
---

### 👨‍💻 Base of Operations
**Computer Engineering Undergrad @ UIT - VNUHCM** | 📍 Ho Chi Minh City, Vietnam

I am a Computer Engineering student currently building my foundational skills in digital logic, computer architecture, and hardware-software interaction.

### 📚 Academic Focus & Coursework
* ⚙️ **Digital Logic & RTL Design:** Verilog/SystemVerilog, digital circuit simulation.
* 🧠 **Computer Architecture:** RISC-V basics (RV32/RV64), multi-core systems.
* 🔬 **VLSI & IC Design:** Schematic capture, physical layout, DRC/LVS.
* 🔌 **Embedded Systems:** C/C++ programming, microcontroller firmware.

### ⚡ About Me
* Passionate about low-level hardware architecture and eager to contribute to real-world SoC projects.
* Active member of the English Speaking Club (ESC) at VNUHCM Dormitory, focusing on improving technical communication and soft skills.
* Always open to learning new EDA tools and improving my engineering mindset step by step.

📫 **Connect with me:** [LinkedIn](https://www.linkedin.com/in/huy-nguyengia) | ✉️ huyng5131@gmail.com
