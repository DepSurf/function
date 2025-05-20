# Function: <code>unregister_kprobes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8112e190)
Location: kernel/kprobes.c:1689
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_kprobes
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_kprobes
```
**Symbols:**

```
ffffffff8112e190-ffffffff8112e232: unregister_kprobes.part.20 (STB_LOCAL)
ffffffff8112e240-ffffffff8112e255: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811364e6)
Location: kernel/kprobes.c:1689
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_kprobes
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_kprobes
```
**Symbols:**

```
ffffffff81136420-ffffffff811364bd: unregister_kprobes.part.22 (STB_LOCAL)
ffffffff811364c0-ffffffff811364d5: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81140266)
Location: kernel/kprobes.c:1689
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_kprobes
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:register_kprobes
```
**Symbols:**

```
ffffffff811401a0-ffffffff8114023d: unregister_kprobes.part.24 (STB_LOCAL)
ffffffff81140240-ffffffff81140255: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811415f6)
Location: kernel/kprobes.c:1736
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff81141530-ffffffff811415c7: unregister_kprobes.part.22 (STB_LOCAL)
ffffffff811415d0-ffffffff811415e6: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8114e496)
Location: kernel/kprobes.c:1738
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff8114e3d0-ffffffff8114e467: unregister_kprobes.part.22 (STB_LOCAL)
ffffffff8114e470-ffffffff8114e486: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff8115cd00)
Location: kernel/kprobes.c:1782
Inline: True
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff8115cd00-ffffffff8115cd84: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/kprobes.c (ffffffff81169970)
Location: kernel/kprobes.c:1770
Inline: True
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff81169970-ffffffff811699f4: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81176905)
Location: kernel/kprobes.c:1774
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff81176840-ffffffff811768dc: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff811768e0-ffffffff811768f5: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81182835)
Location: kernel/kprobes.c:1817
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff81182770-ffffffff8118280c: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff81182810-ffffffff81182825: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81196ad5)
Location: kernel/kprobes.c:1861
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff811968f0-ffffffff8119698c: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff81196990-ffffffff811969a5: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81193be5)
Location: kernel/kprobes.c:1825
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff81193950-ffffffff811939ec: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff811939f0-ffffffff81193a05: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81194bc5)
Location: kernel/kprobes.c:1830
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff81194930-ffffffff811949cc: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff811949d0-ffffffff811949e5: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811bda85)
Location: kernel/kprobes.c:1822
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff811bd840-ffffffff811bd8dc: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff811bd8e0-ffffffff811bd8f5: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811f0af5)
Location: kernel/kprobes.c:1826
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff811f08f0-ffffffff811f099a: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff811f09a0-ffffffff811f09c5: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81237935)
Location: kernel/kprobes.c:1834
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff812376e0-ffffffff8123778a: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff812377a0-ffffffff812377c5: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8124e9f5)
Location: kernel/kprobes.c:1846
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff8124e7a0-ffffffff8124e84a: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff8124e860-ffffffff8124e885: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81268925)
Location: kernel/kprobes.c:1846
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff812686d0-ffffffff8126877a: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff81268790-ffffffff812687b5: unregister_kprobes (STB_GLOBAL)
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
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffff8000101f7534)
Location: kernel/kprobes.c:1817
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffff8000101f7420-ffff8000101f74e0: unregister_kprobes.part.0 (STB_LOCAL)
ffff8000101f74e0-ffff8000101f751c: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c0437ec4)
Location: kernel/kprobes.c:1817
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
c0437df4-c0437e88: unregister_kprobes.part.0 (STB_LOCAL)
c0437e88-c0437eac: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (c00000000026e95c)
Location: kernel/kprobes.c:1817
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
c00000000026e800-c00000000026e920: unregister_kprobes.part.0 (STB_LOCAL)
c00000000026e920-c00000000026e93c: unregister_kprobes (STB_GLOBAL)
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
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8117ae55)
Location: kernel/kprobes.c:1817
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff8117ad90-ffffffff8117ae2c: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff8117ae30-ffffffff8117ae45: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff8116dff5)
Location: kernel/kprobes.c:1817
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff8116df30-ffffffff8116dfcc: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff8116dfd0-ffffffff8116dfe5: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff81178c25)
Location: kernel/kprobes.c:1817
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff81178b60-ffffffff81178bfc: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff81178c00-ffffffff81178c15: unregister_kprobes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void unregister_kprobes(struct kprobe **kps, int num);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/kprobes.c (ffffffff811864f5)
Location: kernel/kprobes.c:1817
Inline: True
Inline callers:
  - kernel/kprobes.c:unregister_kprobe
Direct callers:
  - kernel/kprobes.c:unregister_kprobe
```
**Symbols:**

```
ffffffff81186430-ffffffff811864cc: unregister_kprobes.part.0 (STB_LOCAL)
ffffffff811864d0-ffffffff811864e5: unregister_kprobes (STB_GLOBAL)
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
