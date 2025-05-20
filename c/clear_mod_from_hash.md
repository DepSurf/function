# Function: <code>clear_mod_from_hash</code>

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
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811620d0)
Location: kernel/trace/ftrace.c:5679
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff811620d0-ffffffff8116216d: clear_mod_from_hash.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81170fa0)
Location: kernel/trace/ftrace.c:5665
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff81170fa0-ffffffff8117103d: clear_mod_from_hash.isra.18 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8117eb60)
Location: kernel/trace/ftrace.c:5625
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff8117eb60-ffffffff8117ebfd: clear_mod_from_hash.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118ba10)
Location: kernel/trace/ftrace.c:5673
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff8118ba10-ffffffff8118ba9e: clear_mod_from_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811978b0)
Location: kernel/trace/ftrace.c:5710
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff811978b0-ffffffff8119793e: clear_mod_from_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clear_mod_from_hash(struct ftrace_page *pg, struct ftrace_hash *hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811acdd0)
Location: kernel/trace/ftrace.c:6201
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff811acdd0-ffffffff811ace60: clear_mod_from_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clear_mod_from_hash(struct ftrace_page *pg, struct ftrace_hash *hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811aa6e0)
Location: kernel/trace/ftrace.c:6339
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff811aa6e0-ffffffff811aa770: clear_mod_from_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clear_mod_from_hash(struct ftrace_page *pg, struct ftrace_hash *hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff811ab2c0)
Location: kernel/trace/ftrace.c:6344
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff811ab2c0-ffffffff811ab354: clear_mod_from_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void clear_mod_from_hash(struct ftrace_page *pg, struct ftrace_hash *hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (0)
Location: kernel/trace/ftrace.c:6345
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff811d4fa0-ffffffff811d505f: clear_mod_from_hash (STB_LOCAL)
ffffffff81cb418c-ffffffff81cb41b0: clear_mod_from_hash.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81210c45)
Location: kernel/trace/ftrace.c:6767
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff8120a160-ffffffff8120a225: clear_mod_from_hash.part.0 (STB_LOCAL)
ffffffff81e65064-ffffffff81e65088: clear_mod_from_hash.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8125a0d5)
Location: kernel/trace/ftrace.c:6883
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff81252810-ffffffff812528d5: clear_mod_from_hash.part.0 (STB_LOCAL)
ffffffff8205cb57-ffffffff8205cb7b: clear_mod_from_hash.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81271421)
Location: kernel/trace/ftrace.c:6698
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff81269ce0-ffffffff81269da5: clear_mod_from_hash.part.0 (STB_LOCAL)
ffffffff820db508-ffffffff820db52c: clear_mod_from_hash.part.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8128b8a4)
Location: kernel/trace/ftrace.c:6702
Inline: True
Inline callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff81283e50-ffffffff81283f15: clear_mod_from_hash.part.0 (STB_LOCAL)
ffffffff821b71df-ffffffff821b7203: clear_mod_from_hash.part.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffff80001020fe80)
Location: kernel/trace/ftrace.c:5710
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffff80001020fe80-ffff80001020ff20: clear_mod_from_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void clear_mod_from_hash(struct ftrace_page *pg, struct ftrace_hash *hash);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/trace/ftrace.c (c044f124)
Location: kernel/trace/ftrace.c:5710
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
c044f124-c044f1d0: clear_mod_from_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (c00000000028f2c0)
Location: kernel/trace/ftrace.c:5710
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
c00000000028f2c0-c00000000028f384: clear_mod_from_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffe000170c72)
Location: kernel/trace/ftrace.c:5710
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffe000170c72-ffffffe000170cfe: clear_mod_from_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118fed0)
Location: kernel/trace/ftrace.c:5710
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff8118fed0-ffffffff8118ff5e: clear_mod_from_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff81183110)
Location: kernel/trace/ftrace.c:5710
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff81183110-ffffffff8118319e: clear_mod_from_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8118dca0)
Location: kernel/trace/ftrace.c:5710
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff8118dca0-ffffffff8118dd2e: clear_mod_from_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/trace/ftrace.c (ffffffff8119b830)
Location: kernel/trace/ftrace.c:5710
Inline: True
Direct callers:
  - kernel/trace/ftrace.c:ftrace_release_mod
  - kernel/trace/ftrace.c:ftrace_release_mod
```
**Symbols:**

```
ffffffff8119b830-ffffffff8119b8be: clear_mod_from_hash.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
