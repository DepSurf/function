# Function: <code>reloc_insn_imm</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int reloc_insn_imm(enum aarch64_reloc_op op, __le32 *place, u64 val, int lsb, int len, enum aarch64_insn_imm_type imm_type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/module.c (ffff8000100a1e28)
Location: arch/arm64/kernel/module.c:193
Inline: False
Direct callers:
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:apply_relocate_add
  - arch/arm64/kernel/module.c:apply_relocate_add
```
**Symbols:**

```
ffff8000100a1e28-ffff8000100a1ed8: reloc_insn_imm (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
