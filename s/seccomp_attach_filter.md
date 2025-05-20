# Function: <code>seccomp_attach_filter</code>

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
In kernel/seccomp.c (ffffffff8113b9b5)
Location: kernel/seccomp.c:422
Inline: True
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
In kernel/seccomp.c (ffffffff81144170)
Location: kernel/seccomp.c:422
Inline: True
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
In kernel/seccomp.c (ffffffff8114e01f)
Location: kernel/seccomp.c:421
Inline: True
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
In kernel/seccomp.c (ffffffff811506bd)
Location: kernel/seccomp.c:433
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
In kernel/seccomp.c (ffffffff8115c8f1)
Location: kernel/seccomp.c:435
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
In kernel/seccomp.c (ffffffff8116bbcb)
Location: kernel/seccomp.c:444
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
In kernel/seccomp.c (ffffffff811795a4)
Location: kernel/seccomp.c:505
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:510
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81185e80-ffffffff81186105: seccomp_attach_filter (STB_LOCAL)
ffffffff81186c5d-ffffffff81186c75: seccomp_attach_filter.cold (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff81191f9c)
Location: kernel/seccomp.c:511
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a6cd0)
Location: kernel/seccomp.c:517
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff811a6cd0-ffffffff811a6fed: seccomp_attach_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a42d0)
Location: kernel/seccomp.c:857
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff811a42d0-ffffffff811a46c8: seccomp_attach_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a4dd0)
Location: kernel/seccomp.c:862
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff811a4dd0-ffffffff811a51ba: seccomp_attach_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811ce520)
Location: kernel/seccomp.c:865
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff811ce520-ffffffff811ce90a: seccomp_attach_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81202630)
Location: kernel/seccomp.c:867
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81202630-ffffffff81202a21: seccomp_attach_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8124a480)
Location: kernel/seccomp.c:867
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff8124a480-ffffffff8124a871: seccomp_attach_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81261780)
Location: kernel/seccomp.c:867
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff81261780-ffffffff81261b76: seccomp_attach_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8127b980)
Location: kernel/seccomp.c:876
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffff8127b980-ffffffff8127bd76: seccomp_attach_filter (STB_LOCAL)
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
In kernel/seccomp.c (ffff800010209910)
Location: kernel/seccomp.c:511
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c044855c)
Location: kernel/seccomp.c:511
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
c044855c-c0448870: seccomp_attach_filter (STB_LOCAL)
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
In kernel/seccomp.c (c000000000286c10)
Location: kernel/seccomp.c:511
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int seccomp_attach_filter(unsigned int flags, struct seccomp_filter *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffe00016b7ca)
Location: kernel/seccomp.c:511
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
```
**Symbols:**

```
ffffffe00016b7ca-ffffffe00016b9ee: seccomp_attach_filter (STB_LOCAL)
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
In kernel/seccomp.c (ffffffff8118a5bc)
Location: kernel/seccomp.c:511
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff8117d6ec)
Location: kernel/seccomp.c:511
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff8118838c)
Location: kernel/seccomp.c:511
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
In kernel/seccomp.c (ffffffff81195cec)
Location: kernel/seccomp.c:511
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
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
