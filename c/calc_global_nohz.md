# Function: <code>calc_global_nohz</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810b0f27)
Location: kernel/sched/loadavg.c:305
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810b3a9a)
Location: kernel/sched/loadavg.c:308
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810ba0da)
Location: kernel/sched/loadavg.c:308
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810b4969)
Location: kernel/sched/loadavg.c:309
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810bbc39)
Location: kernel/sched/loadavg.c:310
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810c3325)
Location: kernel/sched/loadavg.c:306
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810cc5d5)
Location: kernel/sched/loadavg.c:291
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d4a05)
Location: kernel/sched/loadavg.c:291
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810defc5)
Location: kernel/sched/loadavg.c:304
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void calc_global_nohz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e7030)
Location: kernel/sched/loadavg.c:304
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
```
**Symbols:**

```
ffffffff810e7030-ffffffff810e7116: calc_global_nohz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void calc_global_nohz();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e4c70)
Location: kernel/sched/loadavg.c:304
Inline: False
Direct callers:
  - kernel/sched/loadavg.c:calc_global_load
```
**Symbols:**

```
ffffffff810e4c70-ffffffff810e4d56: calc_global_nohz (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e6e91)
Location: kernel/sched/loadavg.c:304
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810fe461)
Location: kernel/sched/loadavg.c:304
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff811489fe)
Location: kernel/sched/loadavg.c:303
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8117721e)
Location: kernel/sched/loadavg.c:303
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff81187e6e)
Location: kernel/sched/loadavg.c:303
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/build_utility.c (ffffffff8119661e)
Location: kernel/sched/loadavg.c:303
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:calc_global_load
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffff80001013ead4)
Location: kernel/sched/loadavg.c:304
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (c038ea10)
Location: kernel/sched/loadavg.c:304
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (c00000000018dc38)
Location: kernel/sched/loadavg.c:304
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffe0000ed372)
Location: kernel/sched/loadavg.c:304
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d91b5)
Location: kernel/sched/loadavg.c:304
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810c7bb5)
Location: kernel/sched/loadavg.c:304
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810d54f5)
Location: kernel/sched/loadavg.c:304
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sched/loadavg.c (ffffffff810e0da5)
Location: kernel/sched/loadavg.c:304
Inline: True
Inline callers:
  - kernel/sched/loadavg.c:calc_global_load
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
</ul>
