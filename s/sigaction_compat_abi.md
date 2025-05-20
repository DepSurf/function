# Function: <code>sigaction_compat_abi</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102dd20)
Location: arch/x86/kernel/signal_compat.c:96
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff8102dd20-ffffffff8102dd85: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102bfa0)
Location: arch/x86/kernel/signal_compat.c:96
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff8102bfa0-ffffffff8102c005: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102ccc0)
Location: arch/x86/kernel/signal_compat.c:97
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff8102ccc0-ffffffff8102cd24: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102df60)
Location: arch/x86/kernel/signal_compat.c:164
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff8102df60-ffffffff8102dfc2: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8102f1a0)
Location: arch/x86/kernel/signal_compat.c:164
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff8102f1a0-ffffffff8102f202: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff81030f70)
Location: arch/x86/kernel/signal_compat.c:164
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff81030f70-ffffffff81030fd1: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff81031830)
Location: arch/x86/kernel/signal_compat.c:164
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff81031830-ffffffff81031891: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff81034090)
Location: arch/x86/kernel/signal_compat.c:164
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff81034090-ffffffff810340f1: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff81034ab0)
Location: arch/x86/kernel/signal_compat.c:164
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff81034ab0-ffffffff81034af7: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff81036530)
Location: arch/x86/kernel/signal_compat.c:172
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff81036530-ffffffff81036577: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8103b7d0)
Location: arch/x86/kernel/signal_compat.c:178
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff8103b7d0-ffffffff8103b817: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff81042590)
Location: arch/x86/kernel/signal_compat.c:180
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff81042590-ffffffff810425bf: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff8104bf00)
Location: arch/x86/kernel/signal_compat.c:180
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff8104bf00-ffffffff8104bf2f: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_64.c (ffffffff8104c770)
Location: arch/x86/kernel/signal_64.c:386
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff8104c770-ffffffff8104c79f: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_64.c (ffffffff810539f0)
Location: arch/x86/kernel/signal_64.c:392
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff810539f0-ffffffff81053a1f: sigaction_compat_abi (STB_GLOBAL)
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
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff8000101129f0)
Location: kernel/signal.c:3949
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffff8000101129f0-ffff800010112a08: sigaction_compat_abi (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0369b68)
Location: kernel/signal.c:3949
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
c0369b68-c0369b80: sigaction_compat_abi (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c00000000015a4a0)
Location: kernel/signal.c:3949
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
c00000000015a4a0-c00000000015a4ac: sigaction_compat_abi (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d1a22)
Location: kernel/signal.c:3949
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffe0000d1a22-ffffffe0000d1a3c: sigaction_compat_abi (STB_WEAK)
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
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff81031990)
Location: arch/x86/kernel/signal_compat.c:164
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff81031990-ffffffff810319f1: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff81021370)
Location: arch/x86/kernel/signal_compat.c:164
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff81021370-ffffffff810213d1: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff810317f0)
Location: arch/x86/kernel/signal_compat.c:164
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff810317f0-ffffffff81031851: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void sigaction_compat_abi(struct k_sigaction *act, struct k_sigaction *oact);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/signal_compat.c (ffffffff810326a0)
Location: arch/x86/kernel/signal_compat.c:164
Inline: False
Direct callers:
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
  - kernel/signal.c:do_sigaction
```
**Symbols:**

```
ffffffff810326a0-ffffffff81032701: sigaction_compat_abi (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
