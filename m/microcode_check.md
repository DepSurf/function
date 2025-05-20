# Function: <code>microcode_check</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/common.c (ffffffff81041a30)
Location: arch/x86/kernel/cpu/common.c:1758
Inline: False
```
**Symbols:**

```
ffffffff81041a30-ffffffff81041b58: microcode_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1868
Inline: False
```
**Symbols:**

```
ffffffff8104352f-ffffffff8104354c: microcode_check.cold.21 (STB_LOCAL)
ffffffff81043300-ffffffff81043412: microcode_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1889
Inline: False
```
**Symbols:**

```
ffffffff81044bc7-ffffffff81044be4: microcode_check.cold.23 (STB_LOCAL)
ffffffff81044980-ffffffff81044a92: microcode_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1936
Inline: False
```
**Symbols:**

```
ffffffff81047176-ffffffff81047193: microcode_check.cold (STB_LOCAL)
ffffffff81046f00-ffffffff81047017: microcode_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1968
Inline: False
```
**Symbols:**

```
ffffffff810478f9-ffffffff81047916: microcode_check.cold (STB_LOCAL)
ffffffff81047690-ffffffff810477a7: microcode_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1926
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
**Symbols:**

```
ffffffff8104b662-ffffffff8104b67f: microcode_check.cold (STB_LOCAL)
ffffffff8104b3f0-ffffffff8104b502: microcode_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:2021
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
**Symbols:**

```
ffffffff81bd5030-ffffffff81bd504d: microcode_check.cold (STB_LOCAL)
ffffffff8104aac0-ffffffff8104abd2: microcode_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:2025
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
**Symbols:**

```
ffffffff81bc73e4-ffffffff81bc7401: microcode_check.cold (STB_LOCAL)
ffffffff8104c3a0-ffffffff8104c4be: microcode_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:2067
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/core.c:reload_store
```
**Symbols:**

```
ffffffff81c9ab42-ffffffff81c9ab5f: microcode_check.cold (STB_LOCAL)
ffffffff81053650-ffffffff8105376e: microcode_check (STB_GLOBAL)
```
</details>
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1968
Inline: False
```
**Symbols:**

```
ffffffff81047a69-ffffffff81047a86: microcode_check.cold (STB_LOCAL)
ffffffff81047800-ffffffff81047917: microcode_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1968
Inline: False
```
**Symbols:**

```
ffffffff81036d69-ffffffff81036d86: microcode_check.cold (STB_LOCAL)
ffffffff81036b40-ffffffff81036c1f: microcode_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1968
Inline: False
```
**Symbols:**

```
ffffffff810478a9-ffffffff810478c6: microcode_check.cold (STB_LOCAL)
ffffffff81047640-ffffffff81047757: microcode_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void microcode_check();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/common.c (0)
Location: arch/x86/kernel/cpu/common.c:1968
Inline: False
```
**Symbols:**

```
ffffffff81048cb9-ffffffff81048cd6: microcode_check.cold (STB_LOCAL)
ffffffff81048a50-ffffffff81048b67: microcode_check (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Arch</b>
<ul>
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
