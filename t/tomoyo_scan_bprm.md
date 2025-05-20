# Function: <code>tomoyo_scan_bprm</code>

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
In security/tomoyo/condition.c (ffffffff8136c7ac)
Location: security/tomoyo/condition.c:100
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff813a29e9)
Location: security/tomoyo/condition.c:100
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff813b9569)
Location: security/tomoyo/condition.c:100
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff813cfe34)
Location: security/tomoyo/condition.c:100
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff813f62cc)
Location: security/tomoyo/condition.c:101
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff8142739e)
Location: security/tomoyo/condition.c:101
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff81443ae2)
Location: security/tomoyo/condition.c:101
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff81471684)
Location: security/tomoyo/condition.c:105
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff8148b424)
Location: security/tomoyo/condition.c:105
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool tomoyo_scan_bprm(struct tomoyo_execve *ee, const u16 argc, const struct tomoyo_argv *argv, const u16 envc, const struct tomoyo_envp *envp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff814e1bd0)
Location: security/tomoyo/condition.c:105
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
**Symbols:**

```
ffffffff814e1bd0-ffffffff814e20d4: tomoyo_scan_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool tomoyo_scan_bprm(struct tomoyo_execve *ee, const u16 argc, const struct tomoyo_argv *argv, const u16 envc, const struct tomoyo_envp *envp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff814fef50)
Location: security/tomoyo/condition.c:105
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
**Symbols:**

```
ffffffff814fef50-ffffffff814ff454: tomoyo_scan_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool tomoyo_scan_bprm(struct tomoyo_execve *ee, const u16 argc, const struct tomoyo_argv *argv, const u16 envc, const struct tomoyo_envp *envp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/tomoyo/condition.c (ffffffff815059a0)
Location: security/tomoyo/condition.c:105
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
**Symbols:**

```
ffffffff815059a0-ffffffff81505e9f: tomoyo_scan_bprm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool tomoyo_scan_bprm(struct tomoyo_execve *ee, const u16 argc, const struct tomoyo_argv *argv, const u16 envc, const struct tomoyo_envp *envp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/condition.c (0)
Location: security/tomoyo/condition.c:105
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
**Symbols:**

```
ffffffff815627e0-ffffffff81562d48: tomoyo_scan_bprm (STB_LOCAL)
ffffffff81cd5b1a-ffffffff81cd5be9: tomoyo_scan_bprm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool tomoyo_scan_bprm(struct tomoyo_execve *ee, const u16 argc, const struct tomoyo_argv *argv, const u16 envc, const struct tomoyo_envp *envp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/condition.c (0)
Location: security/tomoyo/condition.c:105
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
**Symbols:**

```
ffffffff815fd8c0-ffffffff815fde92: tomoyo_scan_bprm (STB_LOCAL)
ffffffff81e88925-ffffffff81e88a00: tomoyo_scan_bprm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool tomoyo_scan_bprm(struct tomoyo_execve *ee, const u16 argc, const struct tomoyo_argv *argv, const u16 envc, const struct tomoyo_envp *envp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/condition.c (0)
Location: security/tomoyo/condition.c:105
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
**Symbols:**

```
ffffffff816ae740-ffffffff816aed0c: tomoyo_scan_bprm (STB_LOCAL)
ffffffff8207444d-ffffffff82074528: tomoyo_scan_bprm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool tomoyo_scan_bprm(struct tomoyo_execve *ee, const u16 argc, const struct tomoyo_argv *argv, const u16 envc, const struct tomoyo_envp *envp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/condition.c (0)
Location: security/tomoyo/condition.c:105
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
**Symbols:**

```
ffffffff816e7170-ffffffff816e7725: tomoyo_scan_bprm (STB_LOCAL)
ffffffff820f3fd6-ffffffff820f40b1: tomoyo_scan_bprm.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool tomoyo_scan_bprm(struct tomoyo_execve *ee, const u16 argc, const struct tomoyo_argv *argv, const u16 envc, const struct tomoyo_envp *envp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/tomoyo/condition.c (0)
Location: security/tomoyo/condition.c:105
Inline: False
Direct callers:
  - security/tomoyo/condition.c:tomoyo_condition
```
**Symbols:**

```
ffffffff81723e80-ffffffff81724435: tomoyo_scan_bprm (STB_LOCAL)
ffffffff821d141b-ffffffff821d14f6: tomoyo_scan_bprm.cold (STB_LOCAL)
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
In security/tomoyo/condition.c (ffff80001057efcc)
Location: security/tomoyo/condition.c:105
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (c0730e9c)
Location: security/tomoyo/condition.c:105
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (c0000000006ec0bc)
Location: security/tomoyo/condition.c:105
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffe0003cfa04)
Location: security/tomoyo/condition.c:105
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff81483a04)
Location: security/tomoyo/condition.c:105
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff81474424)
Location: security/tomoyo/condition.c:105
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff8147faa4)
Location: security/tomoyo/condition.c:105
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
In security/tomoyo/condition.c (ffffffff814975d1)
Location: security/tomoyo/condition.c:105
Inline: True
Inline callers:
  - security/tomoyo/condition.c:tomoyo_condition
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
