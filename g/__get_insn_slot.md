# Function: <code>__get_insn_slot</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8112e810)
Location: kernel/kprobes.c:147
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8112e810-ffffffff8112e9d1: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81136ab0)
Location: kernel/kprobes.c:147
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81136ab0-ffffffff81136c6f: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81140830)
Location: kernel/kprobes.c:147
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81140830-ffffffff811409ef: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81141d20)
Location: kernel/kprobes.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81141d20-ffffffff81141ecd: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8114ead0)
Location: kernel/kprobes.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8114ead0-ffffffff8114ec83: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115d550)
Location: kernel/kprobes.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8115d550-ffffffff8115d705: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116a180)
Location: kernel/kprobes.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8116a180-ffffffff8116a32a: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (0)
Location: kernel/kprobes.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff811781c4-ffffffff811781da: __get_insn_slot.cold (STB_LOCAL)
ffffffff81176ee0-ffffffff81177078: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81182e10)
Location: kernel/kprobes.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81182e10-ffffffff81182fa1: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81196c90)
Location: kernel/kprobes.c:136
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81196c90-ffffffff81196e17: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81193d40)
Location: kernel/kprobes.c:129
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81193d40-ffffffff81193ef0: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81194d30)
Location: kernel/kprobes.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81194d30-ffffffff81194ee0: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811bdbf0)
Location: kernel/kprobes.c:130
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff811bdbf0-ffffffff811bdda0: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff811f0f10)
Location: kernel/kprobes.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff811f0f10-ffffffff811f10e2: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff812379d0)
Location: kernel/kprobes.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff812379d0-ffffffff81237ba2: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8124ea90)
Location: kernel/kprobes.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8124ea90-ffffffff8124ec82: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff812689c0)
Location: kernel/kprobes.c:144
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff812689c0-ffffffff81268bb2: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffff8000101f8720)
Location: kernel/kprobes.c:131
Inline: False
Direct callers:
  - arch/arm64/kernel/probes/kprobes.c:arch_prepare_kprobe
```
**Symbols:**

```
ffff8000101f8720-ffff8000101f88a0: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c04384e8)
Location: kernel/kprobes.c:131
Inline: False
Direct callers:
  - arch/arm/probes/kprobes/core.c:arch_prepare_kprobe
  - arch/arm/probes/kprobes/opt-arm.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
c04384e8-c04386a4: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (c00000000026f2f0)
Location: kernel/kprobes.c:131
Inline: False
Direct callers:
  - arch/powerpc/kernel/kprobes.c:arch_prepare_kprobe
  - arch/powerpc/kernel/optprobes.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
c00000000026f2f0-c00000000026f4f4: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8117b430)
Location: kernel/kprobes.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8117b430-ffffffff8117b5c1: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8116e5d0)
Location: kernel/kprobes.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff8116e5d0-ffffffff8116e761: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81179200)
Location: kernel/kprobes.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81179200-ffffffff81179391: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
kprobe_opcode_t *__get_insn_slot(struct kprobe_insn_cache *c);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81186ad0)
Location: kernel/kprobes.c:131
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:arch_prepare_kprobe
  - arch/x86/kernel/kprobes/opt.c:arch_prepare_optimized_kprobe
```
**Symbols:**

```
ffffffff81186ad0-ffffffff81186c70: __get_insn_slot (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
