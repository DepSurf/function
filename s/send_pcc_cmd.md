# Function: <code>send_pcc_cmd</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int send_pcc_cmd(u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81525324)
Location: drivers/acpi/cppc_acpi.c:228
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81525324-ffffffff81525508: send_pcc_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int send_pcc_cmd(u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff81537b50)
Location: drivers/acpi/cppc_acpi.c:233
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81537b50-ffffffff81537ddf: send_pcc_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffffffff815993b0)
Location: drivers/acpi/cppc_acpi.c:239
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff815993b0-ffffffff8159964d: send_pcc_cmd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:235
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff815d0c50-ffffffff815d0ebf: send_pcc_cmd (STB_LOCAL)
ffffffff815d2ad7-ffffffff815d2af1: send_pcc_cmd.cold.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:235
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff815ea280-ffffffff815ea4ef: send_pcc_cmd (STB_LOCAL)
ffffffff815ec287-ffffffff815ec2a1: send_pcc_cmd.cold.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:231
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff8161c050-ffffffff8161c2bc: send_pcc_cmd (STB_LOCAL)
ffffffff8161e057-ffffffff8161e071: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:231
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff8163daa0-ffffffff8163dd0c: send_pcc_cmd (STB_LOCAL)
ffffffff8163fb07-ffffffff8163fb21: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:231
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff816eae60-ffffffff816eb0cc: send_pcc_cmd (STB_LOCAL)
ffffffff816ecb5f-ffffffff816ecb79: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:232
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff817085c0-ffffffff8170882c: send_pcc_cmd (STB_LOCAL)
ffffffff81c03293-ffffffff81c032ad: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:223
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff816e9bc0-ffffffff816e9e30: send_pcc_cmd (STB_LOCAL)
ffffffff81bf4c85-ffffffff81bf4c9f: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:223
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81763430-ffffffff81763705: send_pcc_cmd (STB_LOCAL)
ffffffff81cf1f35-ffffffff81cf1f7c: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:236
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81897380-ffffffff81897661: send_pcc_cmd (STB_LOCAL)
ffffffff81eb9ef9-ffffffff81eb9f4e: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:236
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff819df0e0-ffffffff819df3de: send_pcc_cmd (STB_LOCAL)
ffffffff8209289d-ffffffff820928cd: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:236
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
  - drivers/acpi/cppc_acpi.c:cppc_set_auto_sel
  - drivers/acpi/cppc_acpi.c:cppc_get_auto_sel_caps
  - drivers/acpi/cppc_acpi.c:cppc_set_epp_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81a26df0-ffffffff81a270ee: send_pcc_cmd (STB_LOCAL)
ffffffff8211361f-ffffffff8211364f: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:239
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_set_enable
  - drivers/acpi/cppc_acpi.c:cppc_set_auto_sel
  - drivers/acpi/cppc_acpi.c:cppc_get_auto_sel_caps
  - drivers/acpi/cppc_acpi.c:cppc_set_epp_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff81a71e00-ffffffff81a720fe: send_pcc_cmd (STB_LOCAL)
ffffffff821f0f92-ffffffff821f0fc2: send_pcc_cmd.cold (STB_LOCAL)
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
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/acpi/cppc_acpi.c (ffff8000107a8980)
Location: drivers/acpi/cppc_acpi.c:231
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffff8000107a8980-ffff8000107a8c64: send_pcc_cmd (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:231
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff816094d0-ffffffff8160973c: send_pcc_cmd (STB_LOCAL)
ffffffff8160b537-ffffffff8160b551: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:231
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff815fb110-ffffffff815fb37c: send_pcc_cmd (STB_LOCAL)
ffffffff815fd177-ffffffff815fd191: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:231
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff816318e0-ffffffff81631b4c: send_pcc_cmd (STB_LOCAL)
ffffffff81633947-ffffffff81633961: send_pcc_cmd.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int send_pcc_cmd(int pcc_ss_id, u16 cmd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/acpi/cppc_acpi.c (0)
Location: drivers/acpi/cppc_acpi.c:231
Inline: False
Direct callers:
  - drivers/acpi/cppc_acpi.c:cppc_set_perf
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_ctrs
  - drivers/acpi/cppc_acpi.c:cppc_get_perf_caps
  - drivers/acpi/cppc_acpi.c:cppc_get_desired_perf
  - drivers/acpi/cppc_acpi.c:send_pcc_cmd
```
**Symbols:**

```
ffffffff8164bc10-ffffffff8164be7c: send_pcc_cmd (STB_LOCAL)
ffffffff8164dc73-ffffffff8164dc8d: send_pcc_cmd.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int pcc_ss_id</code>
</li>
<li>
<b>Param reordered. </b>
<code>cmd</code> ➡️ <code>pcc_ss_id, cmd</code>
</li>
</ul>
</details>
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
