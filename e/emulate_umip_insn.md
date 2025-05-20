# Function: <code>emulate_umip_insn</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff8106d1a2)
Location: arch/x86/kernel/umip.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
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
In arch/x86/kernel/umip.c (ffffffff810700df)
Location: arch/x86/kernel/umip.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
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
In arch/x86/kernel/umip.c (ffffffff8107603f)
Location: arch/x86/kernel/umip.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff81079c4e)
Location: arch/x86/kernel/umip.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff8107aca0)
Location: arch/x86/kernel/umip.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810820b0)
Location: arch/x86/kernel/umip.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int emulate_umip_insn(struct insn *insn, int umip_inst, unsigned char *data, int *data_size, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:205
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81081960-ffffffff81081c09: emulate_umip_insn (STB_LOCAL)
ffffffff81bd8353-ffffffff81bd835f: emulate_umip_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int emulate_umip_insn(struct insn *insn, int umip_inst, unsigned char *data, int *data_size, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:205
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81082780-ffffffff81082a21: emulate_umip_insn (STB_LOCAL)
ffffffff81bca190-ffffffff81bca19c: emulate_umip_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int emulate_umip_insn(struct insn *insn, int umip_inst, unsigned char *data, int *data_size, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:205
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff81091840-ffffffff81091ae1: emulate_umip_insn (STB_LOCAL)
ffffffff81c9f4f7-ffffffff81c9f503: emulate_umip_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int emulate_umip_insn(struct insn *insn, int umip_inst, unsigned char *data, int *data_size, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/umip.c (0)
Location: arch/x86/kernel/umip.c:205
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810a2a20-ffffffff810a2cd3: emulate_umip_insn (STB_LOCAL)
ffffffff81e4eca2-ffffffff81e4ecae: emulate_umip_insn.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int emulate_umip_insn(struct insn *insn, int umip_inst, unsigned char *data, int *data_size, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810bace0)
Location: arch/x86/kernel/umip.c:205
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810bace0-ffffffff810baf9a: emulate_umip_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int emulate_umip_insn(struct insn *insn, int umip_inst, unsigned char *data, int *data_size, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810bde30)
Location: arch/x86/kernel/umip.c:205
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810bde30-ffffffff810be0d6: emulate_umip_insn (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int emulate_umip_insn(struct insn *insn, int umip_inst, unsigned char *data, int *data_size, bool x86_64);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810c4fb0)
Location: arch/x86/kernel/umip.c:205
Inline: False
Direct callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
**Symbols:**

```
ffffffff810c4fb0-ffffffff810c5256: emulate_umip_insn (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff81079ca0)
Location: arch/x86/kernel/umip.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff810693cc)
Location: arch/x86/kernel/umip.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff81079c50)
Location: arch/x86/kernel/umip.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/umip.c (ffffffff8107bd50)
Location: arch/x86/kernel/umip.c:204
Inline: True
Inline callers:
  - arch/x86/kernel/umip.c:fixup_umip_exception
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
