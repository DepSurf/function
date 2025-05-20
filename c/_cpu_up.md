# Function: <code>_cpu_up</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81081850)
Location: kernel/cpu.c:486
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81081850-ffffffff810819c7: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810847a0)
Location: kernel/cpu.c:930
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff810847a0-ffffffff81084876: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81089740)
Location: kernel/cpu.c:888
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81089740-ffffffff8108980f: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81085c00)
Location: kernel/cpu.c:800
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81085c00-ffffffff81085ccf: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108c870)
Location: kernel/cpu.c:984
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff8108c870-ffffffff8108c9e4: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81090210)
Location: kernel/cpu.c:1070
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81090210-ffffffff81090367: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81098fc0)
Location: kernel/cpu.c:1086
Inline: False
Direct callers:
  - kernel/cpu.c:store_smt_control
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff81098fc0-ffffffff81099104: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d550)
Location: kernel/cpu.c:1098
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff8109d550-ffffffff8109d690: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a3aa0)
Location: kernel/cpu.c:1113
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff810a3aa0-ffffffff810a3be0: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810aaaf0)
Location: kernel/cpu.c:1190
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:thaw_secondary_cpus
```
**Symbols:**

```
ffffffff810aaaf0-ffffffff810aac39: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a6380)
Location: kernel/cpu.c:1194
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:thaw_secondary_cpus
```
**Symbols:**

```
ffffffff810a6380-ffffffff810a64c9: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a72e0)
Location: kernel/cpu.c:1297
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:thaw_secondary_cpus
```
**Symbols:**

```
ffffffff810a72e0-ffffffff810a753c: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810b8cd0)
Location: kernel/cpu.c:1323
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:thaw_secondary_cpus
```
**Symbols:**

```
ffffffff810b8cd0-ffffffff810b8f2e: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810cf610)
Location: kernel/cpu.c:1335
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:thaw_secondary_cpus
```
**Symbols:**

```
ffffffff810cf610-ffffffff810cf87e: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810eda10)
Location: kernel/cpu.c:1359
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:thaw_secondary_cpus
```
**Symbols:**

```
ffffffff810eda10-ffffffff810edc19: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810f9b00)
Location: kernel/cpu.c:1635
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:thaw_secondary_cpus
```
**Symbols:**

```
ffffffff810f9b00-ffffffff810f9d04: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff81102f10)
Location: kernel/cpu.c:1673
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:thaw_secondary_cpus
```
**Symbols:**

```
ffffffff81102f10-ffffffff81103114: _cpu_up (STB_LOCAL)
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
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffff8000100f93e0)
Location: kernel/cpu.c:1113
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffff8000100f93e0-ffff8000100f9594: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c03576d0)
Location: kernel/cpu.c:1113
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
  - kernel/cpu.c:do_cpu_up
```
**Symbols:**

```
c03576d0-c035787c: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (c0000000001401a0)
Location: kernel/cpu.c:1113
Inline: False
Direct callers:
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
c0000000001401a0-c0000000001403d8: _cpu_up (STB_LOCAL)
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
In kernel/cpu.c (ffffffe0000c3e66)
Location: kernel/cpu.c:1113
Inline: True
Inline callers:
  - kernel/cpu.c:cpu_up
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
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d3c0)
Location: kernel/cpu.c:1113
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff8109d3c0-ffffffff8109d500: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8108bde0)
Location: kernel/cpu.c:1113
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff8108bde0-ffffffff8108bf20: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff8109d370)
Location: kernel/cpu.c:1113
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff8109d370-ffffffff8109d4b0: _cpu_up (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int _cpu_up(unsigned int cpu, int tasks_frozen, enum cpuhp_state target);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/cpu.c (ffffffff810a51f0)
Location: kernel/cpu.c:1113
Inline: False
Direct callers:
  - kernel/cpu.c:cpuhp_smt_enable
  - kernel/cpu.c:enable_nonboot_cpus
```
**Symbols:**

```
ffffffff810a51f0-ffffffff810a5330: _cpu_up (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum cpuhp_state target</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
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
