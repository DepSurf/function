# Function: <code>cgroup_ssid_enabled</code>

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
In kernel/cgroup.c (ffffffff8111270d)
Location: kernel/cgroup.c:250
Inline: True
Inline callers:
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:proc_cgroupstats_show
  - kernel/cgroup.c:cgroup_subtree_control_write
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
In kernel/cgroup.c (ffffffff8111a402)
Location: kernel/cgroup.c:259
Inline: True
Inline callers:
  - kernel/cgroup.c:proc_cgroupstats_show
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:parse_cgroupfs_options
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
In kernel/cgroup.c (ffffffff81121e22)
Location: kernel/cgroup.c:262
Inline: True
Inline callers:
  - kernel/cgroup.c:proc_cgroupstats_show
  - kernel/cgroup.c:cgroup_subtree_control_write
  - kernel/cgroup.c:parse_cgroupfs_options
  - kernel/cgroup.c:parse_cgroupfs_options
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81126f0a)
Location: kernel/cgroup/cgroup.c:222
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff81123f20-ffffffff81123f40: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811333b5)
Location: kernel/cgroup/cgroup.c:227
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff8112f8c0-ffffffff8112f8e0: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81141a75)
Location: kernel/cgroup/cgroup.c:230
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff8113dda0-ffffffff8113ddc0: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8114d515)
Location: kernel/cgroup/cgroup.c:235
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:parse_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff81149790-ffffffff811497b0: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff811592f4)
Location: kernel/cgroup/cgroup.c:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff81154dd0-ffffffff81154df0: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81164f54)
Location: kernel/cgroup/cgroup.c:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff81160a00-ffffffff81160a20: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81175ff4)
Location: kernel/cgroup/cgroup.c:233
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff81172170-ffffffff81172190: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81172ce4)
Location: kernel/cgroup/cgroup.c:233
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff8116edc0-ffffffff8116ede0: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff831eaa4b)
Location: kernel/cgroup/cgroup.c:233
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff8116f9f0-ffffffff8116fa10: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff832cf28f)
Location: kernel/cgroup/cgroup.c:257
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff81195e40-ffffffff81195e7c: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff83482fd4)
Location: kernel/cgroup/cgroup.c:258
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff811c5d00-ffffffff811c5d44: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff83eb0809)
Location: kernel/cgroup/cgroup.c:265
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff81208740-ffffffff81208784: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff836d57f9)
Location: kernel/cgroup/cgroup.c:266
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff8121def0-ffffffff8121df34: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff83907b69)
Location: kernel/cgroup/cgroup.c:268
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_init
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:cgroup1_parse_param
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff81235b50-ffffffff81235b94: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffff8000101d69c8)
Location: kernel/cgroup/cgroup.c:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffff8000101d1ac0-ffff8000101d1b00: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c04196c0)
Location: kernel/cgroup/cgroup.c:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
c0414a8c-c0414ac4: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (c000000000242a90)
Location: kernel/cgroup/cgroup.c:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
c00000000023c590-c00000000023c5e0: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffe00014fb5e)
Location: kernel/cgroup/cgroup.c:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffe00014b5a4-ffffffe00014b5da: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115d574)
Location: kernel/cgroup/cgroup.c:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff81159020-ffffffff81159040: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81150864)
Location: kernel/cgroup/cgroup.c:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff8114c330-ffffffff8114c350: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff8115b344)
Location: kernel/cgroup/cgroup.c:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff81156df0-ffffffff81156e10: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool cgroup_ssid_enabled(int ssid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup.c (ffffffff81168424)
Location: kernel/cgroup/cgroup.c:237
Inline: True
Inline callers:
  - kernel/cgroup/cgroup.c:cgroup_subtree_control_write
Direct callers:
  - kernel/cgroup/cgroup-v1.c:check_cgroupfs_options
  - kernel/cgroup/cgroup-v1.c:proc_cgroupstats_show
```
**Symbols:**

```
ffffffff81163db0-ffffffff81163dd0: cgroup_ssid_enabled (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
