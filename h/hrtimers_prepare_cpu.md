# Function: <code>hrtimers_prepare_cpu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81fa9065)
Location: kernel/time/hrtimer.c:1593
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff810f6ea0-ffffffff810f6efa: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81fe4efd)
Location: kernel/time/hrtimer.c:1593
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff810fdf60-ffffffff810fdfba: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff820c5b9c)
Location: kernel/time/hrtimer.c:1584
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff811002a0-ffffffff811002fa: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff826ce233)
Location: kernel/time/hrtimer.c:1589
Inline: True
Inline callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff8110b090-ffffffff8110b0f9: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81116be0)
Location: kernel/time/hrtimer.c:1804
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff81116be0-ffffffff81116c56: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81122220)
Location: kernel/time/hrtimer.c:1794
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff81122220-ffffffff81122296: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112cb50)
Location: kernel/time/hrtimer.c:1794
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff8112cb50-ffffffff8112cbc6: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81138b30)
Location: kernel/time/hrtimer.c:1988
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff81138b30-ffffffff81138ba6: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81147a10)
Location: kernel/time/hrtimer.c:1995
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff81147a10-ffffffff81147a85: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81143ea0)
Location: kernel/time/hrtimer.c:2012
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff81143ea0-ffffffff81143f1c: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81145030)
Location: kernel/time/hrtimer.c:2012
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff81145030-ffffffff811450ac: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81168880)
Location: kernel/time/hrtimer.c:2160
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff81168880-ffffffff81168933: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8119c3d0)
Location: kernel/time/hrtimer.c:2160
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff8119c3d0-ffffffff8119c48f: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811dad90)
Location: kernel/time/hrtimer.c:2162
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff811dad90-ffffffff811dae4f: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811ef2a0)
Location: kernel/time/hrtimer.c:2165
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff811ef2a0-ffffffff811ef370: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81205420)
Location: kernel/time/hrtimer.c:2166
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff81205420-ffffffff812054fd: hrtimers_prepare_cpu (STB_GLOBAL)
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
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffff8000101a2688)
Location: kernel/time/hrtimer.c:1988
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffff8000101a2688-ffff8000101a270c: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c03ec374)
Location: kernel/time/hrtimer.c:1988
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
c03ec374-c03ec3f8: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (c000000000203be0)
Location: kernel/time/hrtimer.c:1988
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
c000000000203be0-c000000000203c6c: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffe00012f652)
Location: kernel/time/hrtimer.c:1988
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffe00012f652-ffffffe00012f6cc: hrtimers_prepare_cpu (STB_GLOBAL)
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
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff811312e0)
Location: kernel/time/hrtimer.c:1988
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff811312e0-ffffffff81131356: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff81123d50)
Location: kernel/time/hrtimer.c:1988
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff81123d50-ffffffff81123dc6: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8112f000)
Location: kernel/time/hrtimer.c:1988
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff8112f000-ffffffff8112f076: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int hrtimers_prepare_cpu(unsigned int cpu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/time/hrtimer.c (ffffffff8113ba00)
Location: kernel/time/hrtimer.c:1988
Inline: False
Direct callers:
  - kernel/time/hrtimer.c:hrtimers_init
```
**Symbols:**

```
ffffffff8113ba00-ffffffff8113ba76: hrtimers_prepare_cpu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
