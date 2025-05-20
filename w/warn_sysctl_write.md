# Function: <code>warn_sysctl_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffff81087cb0)
Location: kernel/sysctl.c:1879
Inline: True
Inline callers:
  - kernel/sysctl.c:proc_dostring
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
Direct callers:
  - kernel/sysctl.c:proc_dostring
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
```
**Symbols:**

```
ffffffff81087cb0-ffffffff81087ce1: warn_sysctl_write.isra.5.part.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffff8108bd12)
Location: kernel/sysctl.c:1999
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/sysctl.c:proc_dostring
Direct callers:
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/sysctl.c:proc_dostring
```
**Symbols:**

```
ffffffff8108ab30-ffffffff8108ab61: warn_sysctl_write.isra.7.part.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/sysctl.c (ffffffff81090c75)
Location: kernel/sysctl.c:1984
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/sysctl.c:proc_dostring
Direct callers:
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_dointvec
  - kernel/sysctl.c:proc_dostring
```
**Symbols:**

```
ffffffff8108fa80-ffffffff8108fab1: warn_sysctl_write.isra.7.part.8 (STB_LOCAL)
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
In kernel/sysctl.c (ffffffff8108cb76)
Location: kernel/sysctl.c:1982
Inline: True
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
In kernel/sysctl.c (ffffffff810937e6)
Location: kernel/sysctl.c:1974
Inline: True
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
In kernel/sysctl.c (ffffffff81097256)
Location: kernel/sysctl.c:1979
Inline: True
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
In kernel/sysctl.c (ffffffff8109f5cf)
Location: kernel/sysctl.c:2027
Inline: True
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
In kernel/sysctl.c (ffffffff810a3ca3)
Location: kernel/sysctl.c:2077
Inline: True
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
In kernel/sysctl.c (ffffffff810aa273)
Location: kernel/sysctl.c:2079
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810b2e11)
Location: kernel/sysctl.c:308
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:do_proc_douintvec_w
  - kernel/sysctl.c:__do_proc_dointvec
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/sysctl.c (ffffffff810ae641)
Location: kernel/sysctl.c:307
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:do_proc_douintvec_w
  - kernel/sysctl.c:__do_proc_dointvec
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
In kernel/sysctl.c (ffffffff810af5d4)
Location: kernel/sysctl.c:319
Inline: True
Inline callers:
  - kernel/sysctl.c:__do_proc_doulongvec_minmax
  - kernel/sysctl.c:__do_proc_douintvec
  - kernel/sysctl.c:__do_proc_dointvec
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
In kernel/sysctl.c (ffffffff810c0610)
Location: kernel/sysctl.c:328
Inline: True
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
In kernel/sysctl.c (ffffffff810d800d)
Location: kernel/sysctl.c:208
Inline: True
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
In kernel/sysctl.c (ffffffff810f7b3d)
Location: kernel/sysctl.c:210
Inline: True
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
In kernel/sysctl.c (ffffffff81103f37)
Location: kernel/sysctl.c:209
Inline: True
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
In kernel/sysctl.c (ffffffff8110d887)
Location: kernel/sysctl.c:209
Inline: True
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
In kernel/sysctl.c (ffff8000101026cc)
Location: kernel/sysctl.c:2079
Inline: True
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
In kernel/sysctl.c (c035e960)
Location: kernel/sysctl.c:2079
Inline: True
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
In kernel/sysctl.c (c000000000149e50)
Location: kernel/sysctl.c:2079
Inline: True
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
In kernel/sysctl.c (ffffffe0000c92c0)
Location: kernel/sysctl.c:2079
Inline: True
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
In kernel/sysctl.c (ffffffff810a3b93)
Location: kernel/sysctl.c:2079
Inline: True
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
In kernel/sysctl.c (ffffffff81092573)
Location: kernel/sysctl.c:2079
Inline: True
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
In kernel/sysctl.c (ffffffff810a3b43)
Location: kernel/sysctl.c:2079
Inline: True
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
In kernel/sysctl.c (ffffffff810abc03)
Location: kernel/sysctl.c:2079
Inline: True
```
</details>
</li>
</ul>

## Differences
