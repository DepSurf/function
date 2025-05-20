# Function: <code>unregister_kretprobes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8112e710)
Location: kernel/kprobes.c:1914
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
  - kernel/kprobes.c:register_kretprobes
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
  - kernel/kprobes.c:register_kretprobes
```
**Symbols:**

```
ffffffff8112e710-ffffffff8112e7ba: unregister_kretprobes.part.22 (STB_LOCAL)
ffffffff8112e7c0-ffffffff8112e7d5: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81136a86)
Location: kernel/kprobes.c:1914
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
  - kernel/kprobes.c:register_kretprobes
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
  - kernel/kprobes.c:register_kretprobes
```
**Symbols:**

```
ffffffff811369b0-ffffffff81136a56: unregister_kretprobes.part.24 (STB_LOCAL)
ffffffff81136a60-ffffffff81136a75: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81140806)
Location: kernel/kprobes.c:1914
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
  - kernel/kprobes.c:register_kretprobes
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
  - kernel/kprobes.c:register_kretprobes
```
**Symbols:**

```
ffffffff81140730-ffffffff811407d6: unregister_kretprobes.part.26 (STB_LOCAL)
ffffffff811407e0-ffffffff811407f5: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81141b86)
Location: kernel/kprobes.c:1996
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff81141ac0-ffffffff81141b60: unregister_kretprobes.part.24 (STB_LOCAL)
ffffffff81141b60-ffffffff81141b76: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8114e936)
Location: kernel/kprobes.c:2000
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff8114e870-ffffffff8114e910: unregister_kretprobes.part.23 (STB_LOCAL)
ffffffff8114e910-ffffffff8114e926: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115d420)
Location: kernel/kprobes.c:2044
Inline: True
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff8115d420-ffffffff8115d4b0: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81169f90)
Location: kernel/kprobes.c:1960
Inline: True
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff81169f90-ffffffff8116a020: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81176e45)
Location: kernel/kprobes.c:1964
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff81176d70-ffffffff81176e14: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff81176e20-ffffffff81176e35: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81182d75)
Location: kernel/kprobes.c:2007
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff81182ca0-ffffffff81182d44: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff81182d50-ffffffff81182d65: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81196b35)
Location: kernel/kprobes.c:2051
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff811969b0-ffffffff81196a54: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff81196a60-ffffffff81196a75: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81193b6e)
Location: kernel/kprobes.c:2076
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff81193a10-ffffffff81193b3f: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff81193b40-ffffffff81193b55: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81194b4e)
Location: kernel/kprobes.c:2081
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff811949f0-ffffffff81194b1e: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff81194b20-ffffffff81194b35: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811bda5e)
Location: kernel/kprobes.c:2075
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff811bd900-ffffffff811bda2e: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff811bda30-ffffffff811bda45: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811f0ace)
Location: kernel/kprobes.c:2288
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff811f09d0-ffffffff811f0a87: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff811f0a90-ffffffff811f0ab5: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff812378fe)
Location: kernel/kprobes.c:2292
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff812377e0-ffffffff81237897: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff812378b0-ffffffff812378d5: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8124e9be)
Location: kernel/kprobes.c:2305
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff8124e8a0-ffffffff8124e957: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff8124e970-ffffffff8124e995: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff812688ee)
Location: kernel/kprobes.c:2290
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff812687d0-ffffffff81268887: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff812688a0-ffffffff812688c5: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffff8000101f7c5c)
Location: kernel/kprobes.c:2007
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffff8000101f7b40-ffff8000101f7c08: unregister_kretprobes.part.0 (STB_LOCAL)
ffff8000101f7c08-ffff8000101f7c44: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c04383a0)
Location: kernel/kprobes.c:2007
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
c04382c8-c0438364: unregister_kretprobes.part.0 (STB_LOCAL)
c0438364-c0438388: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c00000000026f0ec)
Location: kernel/kprobes.c:2007
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
c00000000026ef80-c00000000026f0b0: unregister_kretprobes.part.0 (STB_LOCAL)
c00000000026f0b0-c00000000026f0cc: unregister_kretprobes (STB_GLOBAL)
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8117b395)
Location: kernel/kprobes.c:2007
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff8117b2c0-ffffffff8117b364: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff8117b370-ffffffff8117b385: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8116e535)
Location: kernel/kprobes.c:2007
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff8116e460-ffffffff8116e504: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff8116e510-ffffffff8116e525: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81179165)
Location: kernel/kprobes.c:2007
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff81179090-ffffffff81179134: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff81179140-ffffffff81179155: unregister_kretprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kretprobes(struct kretprobe **rps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81186a35)
Location: kernel/kprobes.c:2007
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kretprobe
Direct callers:
  - kernel/kprobes.c:unregister_kretprobe
```
**Symbols:**

```
ffffffff81186960-ffffffff81186a04: unregister_kretprobes.part.0 (STB_LOCAL)
ffffffff81186a10-ffffffff81186a25: unregister_kretprobes (STB_GLOBAL)
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
