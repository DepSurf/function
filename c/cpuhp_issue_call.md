# Function: <code>cpuhp_issue_call</code>

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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, int (*cb)(unsigned int), bool bringup);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810840b0)
Location: kernel/cpu.c:1401
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_setup_state
```
**Symbols:**

```
ffffffff810840b0-ffffffff81084144: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81088f10)
Location: kernel/cpu.c:1368
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff81088f10-ffffffff81088fe8: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085f10)
Location: kernel/cpu.c:1292
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff81085f10-ffffffff81085fed: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108cb60)
Location: kernel/cpu.c:1476
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff8108cb60-ffffffff8108cc74: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81090510)
Location: kernel/cpu.c:1558
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff81090510-ffffffff81090629: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810985d0)
Location: kernel/cpu.c:1580
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff810985d0-ffffffff810986e9: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109cba0)
Location: kernel/cpu.c:1606
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff8109cba0-ffffffff8109cca9: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a30f0)
Location: kernel/cpu.c:1621
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff810a30f0-ffffffff810a31f9: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aa1c0)
Location: kernel/cpu.c:1752
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff810aa1c0-ffffffff810aa231: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5a50)
Location: kernel/cpu.c:1763
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff810a5a50-ffffffff810a5ac1: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6770)
Location: kernel/cpu.c:1867
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff810a6770-ffffffff810a690c: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b8080)
Location: kernel/cpu.c:1897
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff810b8080-ffffffff810b81e7: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ce8b0)
Location: kernel/cpu.c:1919
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff810ce8b0-ffffffff810cea24: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ecc60)
Location: kernel/cpu.c:1943
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff810ecc60-ffffffff810ecdd4: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f8790)
Location: kernel/cpu.c:2328
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff810f8790-ffffffff810f88f9: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81101ba0)
Location: kernel/cpu.c:2374
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff81101ba0-ffffffff81101d09: cpuhp_issue_call (STB_LOCAL)
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f8730)
Location: kernel/cpu.c:1621
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffff8000100f8730-ffff8000100f88a4: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0356a10)
Location: kernel/cpu.c:1621
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
c0356a10-c0356b50: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013f0d0)
Location: kernel/cpu.c:1621
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
c00000000013f0d0-c00000000013f2b0: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c35b8)
Location: kernel/cpu.c:1621
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffe0000c35b8-ffffffe0000c36da: cpuhp_issue_call (STB_LOCAL)
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
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109ca10)
Location: kernel/cpu.c:1621
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff8109ca10-ffffffff8109cb19: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108b440)
Location: kernel/cpu.c:1621
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff8108b440-ffffffff8108b549: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109c9c0)
Location: kernel/cpu.c:1621
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff8109c9c0-ffffffff8109cac9: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int cpuhp_issue_call(int cpu, enum cpuhp_state state, bool bringup, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4750)
Location: kernel/cpu.c:1621
Inline: True
Direct callers:
  - kernel/cpu.c:__cpuhp_remove_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_remove_instance
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
  - kernel/cpu.c:cpuhp_rollback_install
```
**Symbols:**

```
ffffffff810a4750-ffffffff810a4859: cpuhp_issue_call (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct hlist_node *node</code>
</li>
<li>
<b>Param removed. </b>
<code>int (*cb)(unsigned int)</code>
</li>
<li>
<b>Param reordered. </b>
<code>cpu, state, cb, bringup</code> ➡️ <code>cpu, state, bringup, node</code>
</li>
</ul>
</details>
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
