# Function: <code>madvise_inject_error</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8120ad88)
Location: mm/madvise.c:612
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
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
In mm/madvise.c (ffffffff812240ca)
Location: mm/madvise.c:622
Inline: True
Inline callers:
  - mm/madvise.c:SyS_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:622
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81244e10-ffffffff81244f64: madvise_inject_error (STB_LOCAL)
ffffffff81246884-ffffffff812468f9: madvise_inject_error.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:623
Inline: False
Direct callers:
  - mm/madvise.c:__ia32_sys_madvise
  - mm/madvise.c:__x64_sys_madvise
```
**Symbols:**

```
ffffffff81259460-ffffffff812595ba: madvise_inject_error (STB_LOCAL)
ffffffff8125acab-ffffffff8125ad20: madvise_inject_error.cold.20 (STB_LOCAL)
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
In mm/madvise.c (ffffffff812753b6)
Location: mm/madvise.c:624
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
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
In mm/madvise.c (ffffffff8128432b)
Location: mm/madvise.c:868
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:869
Inline: False
```
**Symbols:**

```
ffffffff812b5c70-ffffffff812b5dd3: madvise_inject_error (STB_LOCAL)
ffffffff812b7aa0-ffffffff812b7b15: madvise_inject_error.cold (STB_LOCAL)
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
In mm/madvise.c (ffffffff812c172f)
Location: mm/madvise.c:877
Inline: True
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
In mm/madvise.c (ffffffff812c8627)
Location: mm/madvise.c:878
Inline: True
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
In mm/madvise.c (ffffffff8130d5b3)
Location: mm/madvise.c:937
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:1082
Inline: False
Direct callers:
  - mm/madvise.c:do_madvise
```
**Symbols:**

```
ffffffff81375f60-ffffffff81376068: madvise_inject_error (STB_LOCAL)
ffffffff81e707d7-ffffffff81e708a1: madvise_inject_error.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int madvise_inject_error(int behavior, long unsigned int start, long unsigned int end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/madvise.c (0)
Location: mm/madvise.c:1114
Inline: False
Direct callers:
  - mm/madvise.c:do_madvise
```
**Symbols:**

```
ffffffff813f37c0-ffffffff813f39a9: madvise_inject_error (STB_LOCAL)
ffffffff820658b0-ffffffff820658ca: madvise_inject_error.cold (STB_LOCAL)
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
In mm/madvise.c (ffffffff8142932a)
Location: mm/madvise.c:1116
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
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
In mm/madvise.c (ffffffff81462b5a)
Location: mm/madvise.c:1110
Inline: True
Inline callers:
  - mm/madvise.c:do_madvise
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
In mm/madvise.c (ffff80001031e760)
Location: mm/madvise.c:868
Inline: True
Inline callers:
  - mm/madvise.c:__arm64_sys_madvise
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (c0000000003f29c8)
Location: mm/madvise.c:868
Inline: True
Inline callers:
  - mm/madvise.c:__se_sys_madvise
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/madvise.c (ffffffff8127c97b)
Location: mm/madvise.c:868
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
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
In mm/madvise.c (ffffffff8126e82b)
Location: mm/madvise.c:868
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
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
In mm/madvise.c (ffffffff8127a71b)
Location: mm/madvise.c:868
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
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
In mm/madvise.c (ffffffff8128a2fb)
Location: mm/madvise.c:868
Inline: True
Inline callers:
  - mm/madvise.c:__do_sys_madvise
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
</ul>
