# Function: <code>unregister_kmmio_probe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81073100)
Location: arch/x86/mm/kmmio.c:502
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
```
**Symbols:**

```
ffffffff81073100-ffffffff8107329b: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff810746b0)
Location: arch/x86/mm/kmmio.c:526
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff810746b0-ffffffff81074856: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81078230)
Location: arch/x86/mm/kmmio.c:526
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff81078230-ffffffff810783d6: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff81076c70)
Location: arch/x86/mm/kmmio.c:526
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff81076c70-ffffffff81076e1f: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/kmmio.c (ffffffff8107ce70)
Location: arch/x86/mm/kmmio.c:528
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff8107ce70-ffffffff8107d034: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:533
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff810806b4-ffffffff810806c5: unregister_kmmio_probe.cold.9 (STB_LOCAL)
ffffffff8107ff20-ffffffff810800c7: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:533
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff81087264-ffffffff81087275: unregister_kmmio_probe.cold.8 (STB_LOCAL)
ffffffff81086a60-ffffffff81086c07: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:533
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff8108adde-ffffffff8108adef: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff8108a660-ffffffff8108a80c: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:533
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff8108ba4e-ffffffff8108ba5f: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff8108b2d0-ffffffff8108b47c: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:528
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:iounmap_trace_core
```
**Symbols:**

```
ffffffff81092e9d-ffffffff81092eae: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff81092660-ffffffff8109280c: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:528
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:iounmap_trace_core
```
**Symbols:**

```
ffffffff81bd9f25-ffffffff81bd9f36: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff81091cf0-ffffffff81091e9c: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:528
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff81bcbf91-ffffffff81bcbfa2: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff81092800-ffffffff810929ac: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:528
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff81ca1e06-ffffffff81ca1e59: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff810a2530-ffffffff810a26dd: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:528
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff81e51461-ffffffff81e514b4: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff810b6b10-ffffffff810b6ce6: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:536
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff8205521c-ffffffff8205525e: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff810d23a0-ffffffff810d2580: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:536
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff820d37eb-ffffffff820d382d: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff810d5810-ffffffff810d59f0: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:536
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff821ae659-ffffffff821ae69b: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff810de010-ffffffff810de21f: unregister_kmmio_probe (STB_GLOBAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:533
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff8108aa0e-ffffffff8108aa1f: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff8108a290-ffffffff8108a43c: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:533
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff810795a0-ffffffff810795b1: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff81078f80-ffffffff8107912c: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:533
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff8108a9be-ffffffff8108a9cf: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff8108a240-ffffffff8108a3ec: unregister_kmmio_probe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void unregister_kmmio_probe(struct kmmio_probe *p);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/kmmio.c (0)
Location: arch/x86/mm/kmmio.c:533
Inline: False
Direct callers:
  - arch/x86/mm/mmio-mod.c:disable_mmiotrace
  - arch/x86/mm/mmio-mod.c:mmiotrace_iounmap
```
**Symbols:**

```
ffffffff8108ccbe-ffffffff8108cccf: unregister_kmmio_probe.cold (STB_LOCAL)
ffffffff8108c4e0-ffffffff8108c68c: unregister_kmmio_probe (STB_GLOBAL)
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
