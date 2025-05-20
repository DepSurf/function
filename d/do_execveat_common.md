# Function: <code>do_execveat_common</code>

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
In fs/exec.c (ffffffff81213e20)
Location: fs/exec.c:1496
Inline: True
Direct callers:
  - fs/exec.c:SyS_execve
  - fs/exec.c:SyS_execveat
  - fs/exec.c:compat_SyS_execve
  - fs/exec.c:compat_SyS_execveat
```
**Symbols:**

```
ffffffff81213e20-ffffffff81214530: do_execveat_common.isra.33 (STB_LOCAL)
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
In fs/exec.c (ffffffff8123ab80)
Location: fs/exec.c:1645
Inline: True
Direct callers:
  - fs/exec.c:compat_SyS_execveat
  - fs/exec.c:compat_SyS_execve
  - fs/exec.c:SyS_execveat
  - fs/exec.c:SyS_execve
```
**Symbols:**

```
ffffffff8123ab80-ffffffff8123b2bb: do_execveat_common.isra.35 (STB_LOCAL)
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
In fs/exec.c (ffffffff8124d930)
Location: fs/exec.c:1671
Inline: True
Direct callers:
  - fs/exec.c:compat_SyS_execveat
  - fs/exec.c:compat_SyS_execve
  - fs/exec.c:SyS_execveat
  - fs/exec.c:SyS_execve
```
**Symbols:**

```
ffffffff8124d930-ffffffff8124e0a4: do_execveat_common.isra.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff812598f0)
Location: fs/exec.c:1703
Inline: True
Direct callers:
  - fs/exec.c:compat_SyS_execveat
  - fs/exec.c:compat_SyS_execve
  - fs/exec.c:SyS_execveat
  - fs/exec.c:SyS_execve
```
**Symbols:**

```
ffffffff812598f0-ffffffff8125a063: do_execveat_common.isra.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff8127bb50)
Location: fs/exec.c:1706
Inline: True
Direct callers:
  - fs/exec.c:compat_SyS_execveat
  - fs/exec.c:compat_SyS_execve
  - fs/exec.c:SyS_execveat
  - fs/exec.c:SyS_execve
```
**Symbols:**

```
ffffffff8127bb50-ffffffff8127c352: do_execveat_common.isra.34 (STB_LOCAL)
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
In fs/exec.c (ffffffff812a3339)
Location: fs/exec.c:1872
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff812b8449)
Location: fs/exec.c:1872
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff812d4906)
Location: fs/exec.c:1875
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff812e6486)
Location: fs/exec.c:1875
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff8131dad8)
Location: fs/exec.c:1983
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:do_execveat
  - fs/exec.c:do_execve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_execveat_common(int fd, struct filename *filename, struct user_arg_ptr argv, struct user_arg_ptr envp, int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81328bf0)
Location: fs/exec.c:1863
Inline: False
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
```
**Symbols:**

```
ffffffff81328bf0-ffffffff81328daf: do_execveat_common (STB_LOCAL)
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
In fs/exec.c (ffffffff8132ea40)
Location: fs/exec.c:1863
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
```
**Symbols:**

```
ffffffff8132ea40-ffffffff8132ebe8: do_execveat_common.isra.0 (STB_LOCAL)
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
In fs/exec.c (ffffffff8137c250)
Location: fs/exec.c:1865
Inline: True
Direct callers:
  - fs/exec.c:__x64_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x64_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
```
**Symbols:**

```
ffffffff8137c250-ffffffff8137c405: do_execveat_common.isra.0 (STB_LOCAL)
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
In fs/exec.c (0)
Location: fs/exec.c:1870
Inline: True
Direct callers:
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
```
**Symbols:**

```
ffffffff813fc550-ffffffff813fc77b: do_execveat_common.isra.0 (STB_LOCAL)
ffffffff81e761ae-ffffffff81e761f8: do_execveat_common.isra.0.cold (STB_LOCAL)
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
In fs/exec.c (0)
Location: fs/exec.c:1880
Inline: True
Direct callers:
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
```
**Symbols:**

```
ffffffff81486000-ffffffff81486257: do_execveat_common.isra.0 (STB_LOCAL)
ffffffff820687df-ffffffff82068802: do_execveat_common.isra.0.cold (STB_LOCAL)
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
In fs/exec.c (0)
Location: fs/exec.c:1887
Inline: True
Direct callers:
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
```
**Symbols:**

```
ffffffff814bab70-ffffffff814badc2: do_execveat_common.isra.0 (STB_LOCAL)
ffffffff820e80e2-ffffffff820e80fd: do_execveat_common.isra.0.cold (STB_LOCAL)
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
In fs/exec.c (0)
Location: fs/exec.c:1908
Inline: True
Direct callers:
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
```
**Symbols:**

```
ffffffff814ed0f0-ffffffff814ed336: do_execveat_common.isra.0 (STB_LOCAL)
ffffffff821c4e1e-ffffffff821c4e39: do_execveat_common.isra.0.cold (STB_LOCAL)
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
In fs/exec.c (ffff80001038e544)
Location: fs/exec.c:1875
Inline: True
Inline callers:
  - fs/exec.c:__arm64_compat_sys_execveat
  - fs/exec.c:__arm64_compat_sys_execve
  - fs/exec.c:__arm64_sys_execveat
  - fs/exec.c:__arm64_sys_execve
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
In fs/exec.c (c0576470)
Location: fs/exec.c:1875
Inline: True
Inline callers:
  - fs/exec.c:__se_sys_execveat
  - fs/exec.c:__se_sys_execve
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
In fs/exec.c (c0000000004869d0)
Location: fs/exec.c:1875
Inline: True
Inline callers:
  - fs/exec.c:__se_compat_sys_execveat
  - fs/exec.c:__se_compat_sys_execve
  - fs/exec.c:__se_sys_execveat
  - fs/exec.c:__se_sys_execve
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
In fs/exec.c (ffffffe00025f41e)
Location: fs/exec.c:1875
Inline: True
Inline callers:
  - fs/exec.c:__se_sys_execveat
  - fs/exec.c:__se_sys_execve
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
In fs/exec.c (ffffffff812dea66)
Location: fs/exec.c:1875
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff812cfd96)
Location: fs/exec.c:1875
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff812dc876)
Location: fs/exec.c:1875
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff812ed5c6)
Location: fs/exec.c:1875
Inline: True
Inline callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
