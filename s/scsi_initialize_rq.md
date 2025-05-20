# Function: <code>scsi_initialize_rq</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81649c80)
Location: drivers/scsi/scsi_lib.c:1114
Inline: False
```
**Symbols:**

```
ffffffff81649c80-ffffffff81649c97: scsi_initialize_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816b6039)
Location: drivers/scsi/scsi_lib.c:1149
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff816b2db0-ffffffff816b2de4: scsi_initialize_rq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff816f22f0)
Location: drivers/scsi/scsi_lib.c:1186
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff816ef010-ffffffff816ef044: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81714fb0)
Location: drivers/scsi/scsi_lib.c:1117
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81712a70-ffffffff81712aa4: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8175078e)
Location: drivers/scsi/scsi_lib.c:1082
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff8174e560-ffffffff8174e594: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817749ae)
Location: drivers/scsi/scsi_lib.c:1082
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81772710-ffffffff81772744: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81837b30)
Location: drivers/scsi/scsi_lib.c:1083
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81834a60-ffffffff81834a97: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81848500)
Location: drivers/scsi/scsi_lib.c:1113
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff818454a0-ffffffff818454d7: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8182b820)
Location: drivers/scsi/scsi_lib.c:1085
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81828620-ffffffff81828657: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff818b73ef)
Location: drivers/scsi/scsi_lib.c:1085
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff818b38a0-ffffffff818b38fd: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff819feb00)
Location: drivers/scsi/scsi_lib.c:1116
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff819feb00-ffffffff819feb6d: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81b7d120)
Location: drivers/scsi/scsi_lib.c:1121
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:__scsi_execute
```
**Symbols:**

```
ffffffff81b7d120-ffffffff81b7d18d: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81bd0ea0)
Location: drivers/scsi/scsi_lib.c:1122
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
```
**Symbols:**

```
ffffffff81bd0ea0-ffffffff81bd0f0d: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81c25b10)
Location: drivers/scsi/scsi_lib.c:1121
Inline: False
Direct callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
  - drivers/scsi/scsi_lib.c:scsi_execute_cmd
```
**Symbols:**

```
ffffffff81c25b10-ffffffff81c25b7d: scsi_initialize_rq (STB_LOCAL)
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
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffff800010978a80)
Location: drivers/scsi/scsi_lib.c:1082
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffff800010975c60-ffff800010975ca0: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c0a4c924)
Location: drivers/scsi/scsi_lib.c:1082
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
c0a4a53c-c0a4a578: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (c000000000a33168)
Location: drivers/scsi/scsi_lib.c:1082
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
c000000000a2ff90-c000000000a2ffec: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffe0005e03b0)
Location: drivers/scsi/scsi_lib.c:1082
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffe0005de346-ffffffe0005de382: scsi_initialize_rq (STB_LOCAL)
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
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff8172909e)
Location: drivers/scsi/scsi_lib.c:1082
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81726e00-ffffffff81726e34: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817024ce)
Location: drivers/scsi/scsi_lib.c:1082
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81700230-ffffffff81700264: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff81767e6e)
Location: drivers/scsi/scsi_lib.c:1082
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81765bd0-ffffffff81765c04: scsi_initialize_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void scsi_initialize_rq(struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/scsi/scsi_lib.c (ffffffff817835ae)
Location: drivers/scsi/scsi_lib.c:1082
Inline: True
Inline callers:
  - drivers/scsi/scsi_lib.c:scsi_init_command
```
**Symbols:**

```
ffffffff81781260-ffffffff81781294: scsi_initialize_rq (STB_LOCAL)
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
