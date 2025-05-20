# Function: <code>clear_page_presence</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81072f80)
Location: arch/x86/mm/kmmio.c:137
Inline: True
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff81072f80-ffffffff810730ad: clear_page_presence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81074550)
Location: arch/x86/mm/kmmio.c:148
Inline: True
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff81074550-ffffffff81074660: clear_page_presence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810780d0)
Location: arch/x86/mm/kmmio.c:148
Inline: True
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff810780d0-ffffffff810781e0: clear_page_presence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81076950)
Location: arch/x86/mm/kmmio.c:148
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff81076950-ffffffff81076a62: clear_page_presence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8107ccf0)
Location: arch/x86/mm/kmmio.c:149
Inline: True
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff8107ccf0-ffffffff8107ce1a: clear_page_presence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:154
Inline: True
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff8107fd10-ffffffff8107fec8: clear_page_presence (STB_LOCAL)
ffffffff8108069c-ffffffff810806b4: clear_page_presence.cold.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108724c)
Location: arch/x86/mm/kmmio.c:154
Inline: True
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff81086850-ffffffff81086a08: clear_page_presence (STB_LOCAL)
ffffffff8108724c-ffffffff81087264: clear_page_presence.cold.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108adc6)
Location: arch/x86/mm/kmmio.c:154
Inline: True
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff8108a460-ffffffff8108a60f: clear_page_presence (STB_LOCAL)
ffffffff8108adb2-ffffffff8108adde: clear_page_presence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108ba36)
Location: arch/x86/mm/kmmio.c:154
Inline: True
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff8108b0d0-ffffffff8108b27f: clear_page_presence (STB_LOCAL)
ffffffff8108ba22-ffffffff8108ba4e: clear_page_presence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:154
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff81092530-ffffffff8109260a: clear_page_presence (STB_LOCAL)
ffffffff81092e71-ffffffff81092e9d: clear_page_presence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:154
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff81091bd0-ffffffff81091c96: clear_page_presence (STB_LOCAL)
ffffffff81bd9ef9-ffffffff81bd9f25: clear_page_presence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:154
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff81092710-ffffffff810927a3: clear_page_presence (STB_LOCAL)
ffffffff81bcbf65-ffffffff81bcbf91: clear_page_presence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:154
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff810a2430-ffffffff810a24c3: clear_page_presence (STB_LOCAL)
ffffffff81ca1dc5-ffffffff81ca1df1: clear_page_presence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:154
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff810b6910-ffffffff810b6a84: clear_page_presence (STB_LOCAL)
ffffffff81e51426-ffffffff81e5144c: clear_page_presence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810d1b70)
Location: arch/x86/mm/kmmio.c:160
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff810d1b70-ffffffff810d1d19: clear_page_presence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810d5020)
Location: arch/x86/mm/kmmio.c:160
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff810d5020-ffffffff810d51c9: clear_page_presence (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810dd8d0)
Location: arch/x86/mm/kmmio.c:160
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff810dd8d0-ffffffff810dd994: clear_page_presence (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108a9f6)
Location: arch/x86/mm/kmmio.c:154
Inline: True
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff8108a090-ffffffff8108a23f: clear_page_presence (STB_LOCAL)
ffffffff8108a9e2-ffffffff8108aa0e: clear_page_presence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:154
Inline: False
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff81078b80-ffffffff81078cbc: clear_page_presence (STB_LOCAL)
ffffffff81079552-ffffffff8107957e: clear_page_presence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108a9a6)
Location: arch/x86/mm/kmmio.c:154
Inline: True
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff8108a040-ffffffff8108a1ef: clear_page_presence (STB_LOCAL)
ffffffff8108a992-ffffffff8108a9be: clear_page_presence.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clear_page_presence(struct kmmio_fault_page *f, bool clear);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8108cca6)
Location: arch/x86/mm/kmmio.c:154
Inline: True
Direct callers:
  - arch/x86/mm/kmmio.c:disarm_kmmio_fault_page
  - arch/x86/mm/kmmio.c:arm_kmmio_fault_page
```
**Symbols:**

```
ffffffff8108c2e0-ffffffff8108c48f: clear_page_presence (STB_LOCAL)
ffffffff8108cc92-ffffffff8108ccbe: clear_page_presence.cold (STB_LOCAL)
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
