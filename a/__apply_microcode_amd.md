# Function: <code>__apply_microcode_amd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc_amd);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e38d)
Location: arch/x86/kernel/cpu/microcode/amd.c:654
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
```
**Symbols:**

```
ffffffff8104e8b0-ffffffff8104e8e6: __apply_microcode_amd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc_amd);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8104e460)
Location: arch/x86/kernel/cpu/microcode/amd.c:666
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_ucode_in_initrd
```
**Symbols:**

```
ffffffff8104e460-ffffffff8104e4da: __apply_microcode_amd (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc_amd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81051030)
Location: arch/x86/kernel/cpu/microcode/amd.c:197
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff81051030-ffffffff810510aa: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81050740)
Location: arch/x86/kernel/cpu/microcode/amd.c:174
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff81050740-ffffffff81050773: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81054350)
Location: arch/x86/kernel/cpu/microcode/amd.c:174
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff81054350-ffffffff81054383: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057120)
Location: arch/x86/kernel/cpu/microcode/amd.c:174
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff81057120-ffffffff81057153: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810546d0)
Location: arch/x86/kernel/cpu/microcode/amd.c:395
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff810546d0-ffffffff81054703: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057920)
Location: arch/x86/kernel/cpu/microcode/amd.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff81057920-ffffffff81057953: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810581f0)
Location: arch/x86/kernel/cpu/microcode/amd.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff810581f0-ffffffff81058223: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105dd80)
Location: arch/x86/kernel/cpu/microcode/amd.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
```
**Symbols:**

```
ffffffff8105dd80-ffffffff8105ddb3: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105ba50)
Location: arch/x86/kernel/cpu/microcode/amd.c:392
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
```
**Symbols:**

```
ffffffff8105ba50-ffffffff8105ba83: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8105c410)
Location: arch/x86/kernel/cpu/microcode/amd.c:392
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
```
**Symbols:**

```
ffffffff8105c410-ffffffff8105c443: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81065ad0)
Location: arch/x86/kernel/cpu/microcode/amd.c:392
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
```
**Symbols:**

```
ffffffff81065ad0-ffffffff81065b03: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810725a0)
Location: arch/x86/kernel/cpu/microcode/amd.c:392
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
```
**Symbols:**

```
ffffffff810725a0-ffffffff810725dd: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81082570)
Location: arch/x86/kernel/cpu/microcode/amd.c:394
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
```
**Symbols:**

```
ffffffff81082570-ffffffff810825ad: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810849e0)
Location: arch/x86/kernel/cpu/microcode/amd.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
```
**Symbols:**

```
ffffffff810849e0-ffffffff81084a1d: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff8108bdd0)
Location: arch/x86/kernel/cpu/microcode/amd.c:418
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_bsp
```
**Symbols:**

```
ffffffff8108bdd0-ffffffff8108be0d: __apply_microcode_amd (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81057d70)
Location: arch/x86/kernel/cpu/microcode/amd.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff81057d70-ffffffff81057da3: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81047f60)
Location: arch/x86/kernel/cpu/microcode/amd.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff81047f60-ffffffff81047f93: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff810581a0)
Location: arch/x86/kernel/cpu/microcode/amd.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff810581a0-ffffffff810581d3: __apply_microcode_amd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __apply_microcode_amd(struct microcode_amd *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/microcode/amd.c (ffffffff81059640)
Location: arch/x86/kernel/cpu/microcode/amd.c:393
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:reload_ucode_amd
  - arch/x86/kernel/cpu/microcode/amd.c:load_ucode_amd_ap
  - arch/x86/kernel/cpu/microcode/amd.c:apply_microcode_early_amd
```
**Symbols:**

```
ffffffff81059640-ffffffff81059673: __apply_microcode_amd (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct microcode_amd *mc</code>
</li>
<li>
<b>Param removed. </b>
<code>struct microcode_amd *mc_amd</code>
</li>
</ul>
</details>
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
