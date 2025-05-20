# Function: <code>run_cmd</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a2900)
Location: kernel/reboot.c:392
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810a2900-ffffffff810a2955: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a6010)
Location: kernel/reboot.c:392
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810a6010-ffffffff810a6065: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810abc70)
Location: kernel/reboot.c:392
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810abc70-ffffffff810abcc5: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810a8840)
Location: kernel/reboot.c:392
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810a8840-ffffffff810a8895: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810af080)
Location: kernel/reboot.c:419
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810af080-ffffffff810af0d5: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b5ec0)
Location: kernel/reboot.c:419
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810b5ec0-ffffffff810b5f15: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810bf150)
Location: kernel/reboot.c:420
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810bf150-ffffffff810bf1a5: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c5260)
Location: kernel/reboot.c:422
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810c5260-ffffffff810c52b7: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810ce360)
Location: kernel/reboot.c:422
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810ce360-ffffffff810ce3b7: run_cmd (STB_LOCAL)
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
In kernel/reboot.c (ffffffff810d82b5)
Location: kernel/reboot.c:422
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
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
In kernel/reboot.c (ffffffff810d3575)
Location: kernel/reboot.c:422
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
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
In kernel/reboot.c (ffffffff810d5265)
Location: kernel/reboot.c:422
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
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
In kernel/reboot.c (ffffffff810e8475)
Location: kernel/reboot.c:423
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81102dc5)
Location: kernel/reboot.c:795
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81128315)
Location: kernel/reboot.c:812
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
```
In mm/vmscan.c (ffffffff81382300)
Location: mm/vmscan.c:5696
Inline: False
Direct callers:
  - mm/vmscan.c:lru_gen_seq_write
```
**Symbols:**

```
ffffffff81382300-ffffffff8138268f: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff811357c5)
Location: kernel/reboot.c:812
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
```
In mm/vmscan.c (ffffffff813b3e70)
Location: mm/vmscan.c:6034
Inline: False
Direct callers:
  - mm/vmscan.c:lru_gen_seq_write
```
**Symbols:**

```
ffffffff813b3e70-ffffffff813b421d: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff81140825)
Location: kernel/reboot.c:829
Inline: True
Inline callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
```
In mm/vmscan.c (ffffffff813dd4f0)
Location: mm/vmscan.c:5383
Inline: False
Direct callers:
  - mm/vmscan.c:lru_gen_seq_write
```
**Symbols:**

```
ffffffff813dd4f0-ffffffff813dd89d: run_cmd (STB_LOCAL)
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
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffff80001012dd78)
Location: kernel/reboot.c:422
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffff80001012dd78-ffff80001012dde8: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c037dbc4)
Location: kernel/reboot.c:422
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
c037dbc4-c037dc28: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (c000000000176c70)
Location: kernel/reboot.c:422
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
c000000000176c70-c000000000176d08: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffe0000e1e0a)
Location: kernel/reboot.c:422
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffe0000e1e0a-ffffffe0000e1e6a: run_cmd (STB_LOCAL)
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
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c86e0)
Location: kernel/reboot.c:422
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810c86e0-ffffffff810c8737: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810b6f00)
Location: kernel/reboot.c:422
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810b6f00-ffffffff810b6f57: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810c7c10)
Location: kernel/reboot.c:422
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810c7c10-ffffffff810c7c67: run_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int run_cmd(const char *cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/reboot.c (ffffffff810d0100)
Location: kernel/reboot.c:422
Inline: False
Direct callers:
  - kernel/reboot.c:reboot_work_func
  - kernel/reboot.c:poweroff_work_func
```
**Symbols:**

```
ffffffff810d0100-ffffffff810d0157: run_cmd (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
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
