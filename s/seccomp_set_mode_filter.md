# Function: <code>seccomp_set_mode_filter</code>

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
In kernel/seccomp.c (ffffffff8113b6dd)
Location: kernel/seccomp.c:764
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
In kernel/seccomp.c (ffffffff81143e76)
Location: kernel/seccomp.c:729
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
In kernel/seccomp.c (ffffffff8114dd36)
Location: kernel/seccomp.c:728
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
In kernel/seccomp.c (ffffffff811503b3)
Location: kernel/seccomp.c:821
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
In kernel/seccomp.c (ffffffff8115c5d7)
Location: kernel/seccomp.c:844
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
In kernel/seccomp.c (ffffffff8116ba71)
Location: kernel/seccomp.c:850
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
In kernel/seccomp.c (ffffffff81179158)
Location: kernel/seccomp.c:1246
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81186110)
Location: kernel/seccomp.c:1251
Inline: False
```
**Symbols:**

```
ffffffff81186110-ffffffff811865a4: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81191de0)
Location: kernel/seccomp.c:1274
Inline: False
```
**Symbols:**

```
ffffffff81191de0-ffffffff81192526: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a6ff0)
Location: kernel/seccomp.c:1292
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
```
**Symbols:**

```
ffffffff811a6ff0-ffffffff811a73e0: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a46d0)
Location: kernel/seccomp.c:1778
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
```
**Symbols:**

```
ffffffff811a46d0-ffffffff811a4b1f: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a51c0)
Location: kernel/seccomp.c:1826
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
```
**Symbols:**

```
ffffffff811a51c0-ffffffff811a56e2: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811ce910)
Location: kernel/seccomp.c:1808
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
```
**Symbols:**

```
ffffffff811ce910-ffffffff811cee32: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81202a30)
Location: kernel/seccomp.c:1837
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
```
**Symbols:**

```
ffffffff81202a30-ffffffff81202f71: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8124a890)
Location: kernel/seccomp.c:1837
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
```
**Symbols:**

```
ffffffff8124a890-ffffffff8124add1: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81261b90)
Location: kernel/seccomp.c:1837
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
```
**Symbols:**

```
ffffffff81261b90-ffffffff812620d1: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8127bd90)
Location: kernel/seccomp.c:1901
Inline: False
Direct callers:
  - kernel/seccomp.c:do_seccomp
```
**Symbols:**

```
ffffffff8127bd90-ffffffff8127c31c: seccomp_set_mode_filter (STB_LOCAL)
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
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffff800010209778)
Location: kernel/seccomp.c:1274
Inline: False
```
**Symbols:**

```
ffff800010209778-ffff800010209e08: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c0448870)
Location: kernel/seccomp.c:1274
Inline: False
```
**Symbols:**

```
c0448870-c0448ce4: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c000000000286920)
Location: kernel/seccomp.c:1274
Inline: False
```
**Symbols:**

```
c000000000286920-c000000000287208: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffe00016b9ee)
Location: kernel/seccomp.c:1274
Inline: False
```
**Symbols:**

```
ffffffe00016b9ee-ffffffe00016bd3e: seccomp_set_mode_filter (STB_LOCAL)
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
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8118a400)
Location: kernel/seccomp.c:1274
Inline: False
```
**Symbols:**

```
ffffffff8118a400-ffffffff8118ab46: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8117d530)
Location: kernel/seccomp.c:1274
Inline: False
```
**Symbols:**

```
ffffffff8117d530-ffffffff8117dc70: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811881d0)
Location: kernel/seccomp.c:1274
Inline: False
```
**Symbols:**

```
ffffffff811881d0-ffffffff81188916: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int seccomp_set_mode_filter(unsigned int flags, const char *filter);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81195b30)
Location: kernel/seccomp.c:1274
Inline: False
```
**Symbols:**

```
ffffffff81195b30-ffffffff81196284: seccomp_set_mode_filter (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
