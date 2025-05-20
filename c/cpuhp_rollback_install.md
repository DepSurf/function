# Function: <code>cpuhp_rollback_install</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81084299)
Location: kernel/cpu.c:1429
Inline: True
Inline callers:
  - kernel/cpu.c:__cpuhp_setup_state
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81088ff0)
Location: kernel/cpu.c:1398
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state
  - kernel/cpu.c:__cpuhp_state_add_instance
```
**Symbols:**

```
ffffffff81088ff0-ffffffff81089079: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085ff0)
Location: kernel/cpu.c:1322
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff81085ff0-ffffffff81086076: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108cc80)
Location: kernel/cpu.c:1510
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff8108cc80-ffffffff8108ccf6: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81090630)
Location: kernel/cpu.c:1592
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff81090630-ffffffff810906a6: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810986f0)
Location: kernel/cpu.c:1614
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff810986f0-ffffffff81098766: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109ccb0)
Location: kernel/cpu.c:1640
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff8109ccb0-ffffffff8109cd25: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3200)
Location: kernel/cpu.c:1655
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff810a3200-ffffffff810a3275: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aa240)
Location: kernel/cpu.c:1786
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff810aa240-ffffffff810aa2b5: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a5ad0)
Location: kernel/cpu.c:1797
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff810a5ad0-ffffffff810a5b45: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6910)
Location: kernel/cpu.c:1900
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff810a6910-ffffffff810a6985: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b81f0)
Location: kernel/cpu.c:1930
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff810b81f0-ffffffff810b828e: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cea30)
Location: kernel/cpu.c:1952
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff810cea30-ffffffff810ceadb: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810ecdf0)
Location: kernel/cpu.c:1976
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff810ecdf0-ffffffff810eceb4: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f8910)
Location: kernel/cpu.c:2361
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff810f8910-ffffffff810f89d4: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81101d20)
Location: kernel/cpu.c:2407
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff81101d20-ffffffff81101de4: cpuhp_rollback_install (STB_LOCAL)
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f88a8)
Location: kernel/cpu.c:1655
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffff8000100f88a8-ffff8000100f8970: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0356b50)
Location: kernel/cpu.c:1655
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
c0356b50-c0356be8: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c00000000013f2b0)
Location: kernel/cpu.c:1655
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
c00000000013f2b0-c00000000013f3bc: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffe0000c36da)
Location: kernel/cpu.c:1655
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffe0000c36da-ffffffe0000c377c: cpuhp_rollback_install (STB_LOCAL)
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
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109cb20)
Location: kernel/cpu.c:1655
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff8109cb20-ffffffff8109cb95: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108b550)
Location: kernel/cpu.c:1655
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff8108b550-ffffffff8108b5c5: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109cad0)
Location: kernel/cpu.c:1655
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff8109cad0-ffffffff8109cb45: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void cpuhp_rollback_install(int failedcpu, enum cpuhp_state state, struct hlist_node *node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a4860)
Location: kernel/cpu.c:1655
Inline: False
Direct callers:
  - kernel/cpu.c:__cpuhp_setup_state_cpuslocked
  - kernel/cpu.c:__cpuhp_state_add_instance_cpuslocked
```
**Symbols:**

```
ffffffff810a4860-ffffffff810a48d5: cpuhp_rollback_install (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
