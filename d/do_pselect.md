# Function: <code>do_pselect</code>

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
In fs/select.c (ffffffff81221cbb)
Location: fs/select.c:646
Inline: True
Inline callers:
  - fs/select.c:SyS_pselect6
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
In fs/select.c (ffffffff81249974)
Location: fs/select.c:650
Inline: True
Inline callers:
  - fs/select.c:SyS_pselect6
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
In fs/select.c (ffffffff8125c954)
Location: fs/select.c:658
Inline: True
Inline callers:
  - fs/select.c:SyS_pselect6
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
In fs/select.c (ffffffff8126a1e3)
Location: fs/select.c:702
Inline: True
Inline callers:
  - fs/select.c:SyS_pselect6
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
In fs/select.c (ffffffff8128ca89)
Location: fs/select.c:701
Inline: True
Inline callers:
  - fs/select.c:SyS_pselect6
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int do_pselect(int n, fd_set *inp, fd_set *outp, fd_set *exp, struct timespec *tsp, const sigset_t *sigmask, size_t sigsetsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (ffffffff812b3f80)
Location: fs/select.c:703
Inline: False
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff812b3f80-ffffffff812b412d: do_pselect (STB_LOCAL)
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
In fs/select.c (ffffffff812c928d)
Location: fs/select.c:728
Inline: True
Inline callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
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
In fs/select.c (ffffffff812e5c91)
Location: fs/select.c:728
Inline: True
Inline callers:
  - fs/select.c:__do_sys_pselect6
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812f76c0)
Location: fs/select.c:728
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff812f76c0-ffffffff812f779f: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff81330260)
Location: fs/select.c:728
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff81330260-ffffffff813303c9: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff8133bbc0)
Location: fs/select.c:728
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff8133bbc0-ffffffff8133bd29: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff813420a0)
Location: fs/select.c:728
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff813420a0-ffffffff81342209: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff8138fa60)
Location: fs/select.c:731
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff8138fa60-ffffffff8138fbc9: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff81410bf0)
Location: fs/select.c:732
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff81410bf0-ffffffff81410d73: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff8149b900)
Location: fs/select.c:732
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff8149b900-ffffffff8149ba83: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff814d0b90)
Location: fs/select.c:732
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff814d0b90-ffffffff814d0d13: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff815034d0)
Location: fs/select.c:732
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff815034d0-ffffffff81503653: do_pselect.constprop.0 (STB_LOCAL)
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
In fs/select.c (ffff8000103a4dac)
Location: fs/select.c:728
Inline: True
Inline callers:
  - fs/select.c:__arm64_sys_pselect6
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int do_pselect(int n, fd_set *inp, fd_set *outp, fd_set *exp, void *tsp, const sigset_t *sigmask, size_t sigsetsize, enum poll_time_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/select.c (c0586588)
Location: fs/select.c:728
Inline: False
Direct callers:
  - fs/select.c:__se_sys_pselect6_time32
  - fs/select.c:__se_sys_pselect6
```
**Symbols:**

```
c0586588-c058669c: do_pselect (STB_LOCAL)
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
In fs/select.c (c00000000049e8d0)
Location: fs/select.c:728
Inline: True
Inline callers:
  - fs/select.c:__se_sys_pselect6
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
In fs/select.c (ffffffe00026b8be)
Location: fs/select.c:728
Inline: True
Inline callers:
  - fs/select.c:__se_sys_pselect6
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812efca0)
Location: fs/select.c:728
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff812efca0-ffffffff812efd7f: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812e08d0)
Location: fs/select.c:728
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff812e08d0-ffffffff812e09af: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812edab0)
Location: fs/select.c:728
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff812edab0-ffffffff812edb8f: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/select.c (ffffffff812feab0)
Location: fs/select.c:728
Inline: True
Direct callers:
  - fs/select.c:__ia32_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
  - fs/select.c:__x64_sys_pselect6
```
**Symbols:**

```
ffffffff812feab0-ffffffff812feb8f: do_pselect.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
