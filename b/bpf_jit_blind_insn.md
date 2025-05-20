# Function: <code>bpf_jit_blind_insn</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8117eccb)
Location: kernel/bpf/core.c:249
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118ab3b)
Location: kernel/bpf/core.c:331
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118f6f1)
Location: kernel/bpf/core.c:548
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119db78)
Location: kernel/bpf/core.c:557
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b23ab)
Location: kernel/bpf/core.c:634
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c0e11)
Location: kernel/bpf/core.c:850
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811ce710)
Location: kernel/bpf/core.c:891
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff811ce710-ffffffff811ceb77: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dad30)
Location: kernel/bpf/core.c:891
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff811dad30-ffffffff811db197: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f78d0)
Location: kernel/bpf/core.c:950
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff811f78d0-ffffffff811f7d38: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f68b0)
Location: kernel/bpf/core.c:947
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff811f68b0-ffffffff811f6d18: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f7700)
Location: kernel/bpf/core.c:953
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff811f7700-ffffffff811f7b6d: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81228cd0)
Location: kernel/bpf/core.c:955
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff81228cd0-ffffffff8122913d: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81269d20)
Location: kernel/bpf/core.c:1242
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff81269d20-ffffffff8126a1d6: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812bed40)
Location: kernel/bpf/core.c:1216
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff812bed40-ffffffff812bf1f6: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e5b20)
Location: kernel/bpf/core.c:1223
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff812e5b20-ffffffff812e5fa1: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81303c30)
Location: kernel/bpf/core.c:1265
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff81303c30-ffffffff813040a4: bpf_jit_blind_insn (STB_LOCAL)
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
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025b890)
Location: kernel/bpf/core.c:891
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffff80001025b890-ffff80001025bbb8: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c048ea7c)
Location: kernel/bpf/core.c:891
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
c048ea7c-c048f13c: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000002ff260)
Location: kernel/bpf/core.c:891
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
c0000000002ff260-c0000000002ff9ac: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019a586)
Location: kernel/bpf/core.c:891
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffe00019a586-ffffffe00019a838: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d3350)
Location: kernel/bpf/core.c:891
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff811d3350-ffffffff811d37b7: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c6110)
Location: kernel/bpf/core.c:891
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff811c6110-ffffffff811c6577: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1120)
Location: kernel/bpf/core.c:891
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff811d1120-ffffffff811d1587: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_jit_blind_insn(const struct bpf_insn *from, const struct bpf_insn *aux, struct bpf_insn *to_buff, bool emit_zext);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811df410)
Location: kernel/bpf/core.c:891
Inline: False
Direct callers:
  - kernel/bpf/core.c:bpf_jit_blind_constants
```
**Symbols:**

```
ffffffff811df410-ffffffff811df877: bpf_jit_blind_insn (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
