# Function: <code>smp_call_on_cpu</code>

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
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81112880)
Location: kernel/smp.c:765
Inline: False
```
**Symbols:**

```
ffffffff81112880-ffffffff811129a0: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81113d70)
Location: kernel/smp.c:776
Inline: False
```
**Symbols:**

```
ffffffff81113d70-ffffffff81113e8b: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8111f330)
Location: kernel/smp.c:778
Inline: False
```
**Symbols:**

```
ffffffff8111f330-ffffffff8111f41f: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8112c660)
Location: kernel/smp.c:780
Inline: False
```
**Symbols:**

```
ffffffff8112c660-ffffffff8112c74f: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81137f30)
Location: kernel/smp.c:787
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81137f30-ffffffff8113801f: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811430c0)
Location: kernel/smp.c:800
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811430c0-ffffffff811431b2: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8114ec00)
Location: kernel/smp.c:800
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8114ec00-ffffffff8114ecf2: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115f260)
Location: kernel/smp.c:859
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8115f260-ffffffff8115f352: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115b200)
Location: kernel/smp.c:996
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8115b200-ffffffff8115b2f2: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8115c590)
Location: kernel/smp.c:1212
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8115c590-ffffffff8115c682: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811816b0)
Location: kernel/smp.c:1220
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811816b0-ffffffff811817a2: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811b7cc0)
Location: kernel/smp.c:1237
Inline: False
Direct callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811b7cc0-ffffffff811b7dbb: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811f8f60)
Location: kernel/smp.c:1238
Inline: False
Direct callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811f8f60-ffffffff811f905b: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8120dc10)
Location: kernel/smp.c:1086
Inline: False
Direct callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8120dc10-ffffffff8120dd0b: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff812253a0)
Location: kernel/smp.c:1106
Inline: False
Direct callers:
  - kernel/watchdog.c:__lockup_detector_reconfigure
  - kernel/watchdog.c:__lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff812253a0-ffffffff8122549b: smp_call_on_cpu (STB_GLOBAL)
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
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffff8000101bcb60)
Location: kernel/smp.c:800
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffff8000101bcb60-ffff8000101bcc84: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c0405254)
Location: kernel/smp.c:800
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
c0405254-c0405380: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (c0000000002233b0)
Location: kernel/smp.c:800
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
c0000000002233b0-c000000000223520: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffe000140e4a)
Location: kernel/smp.c:800
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffe000140e4a-ffffffe000140f58: smp_call_on_cpu (STB_GLOBAL)
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
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81147220)
Location: kernel/smp.c:800
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81147220-ffffffff81147312: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff8113a500)
Location: kernel/smp.c:800
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff8113a500-ffffffff8113a5f2: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff811450d0)
Location: kernel/smp.c:800
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff811450d0-ffffffff811451c2: smp_call_on_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int smp_call_on_cpu(unsigned int cpu, int (*func)(void *), void *par, bool phys);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/smp.c (ffffffff81151cb0)
Location: kernel/smp.c:800
Inline: False
Direct callers:
  - kernel/watchdog.c:lockup_detector_reconfigure
  - kernel/watchdog.c:lockup_detector_reconfigure
```
**Symbols:**

```
ffffffff81151cb0-ffffffff81151da2: smp_call_on_cpu (STB_GLOBAL)
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
