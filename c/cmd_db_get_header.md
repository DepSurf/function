# Function: <code>cmd_db_get_header</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int cmd_db_get_header(const char *id, const struct entry_header **eh, const struct rsc_hdr **rh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/qcom/cmd-db.c (ffff80001081ad80)
Location: drivers/soc/qcom/cmd-db.c:136
Inline: False
Direct callers:
  - drivers/soc/qcom/cmd-db.c:cmd_db_read_slave_id
  - drivers/soc/qcom/cmd-db.c:cmd_db_read_aux_data
  - drivers/soc/qcom/cmd-db.c:cmd_db_read_addr
```
**Symbols:**

```
ffff80001081ad80-ffff80001081ae98: cmd_db_get_header (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cmd_db_get_header(const char *id, const struct entry_header **eh, const struct rsc_hdr **rh);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/soc/qcom/cmd-db.c (c0937b4c)
Location: drivers/soc/qcom/cmd-db.c:136
Inline: False
Direct callers:
  - drivers/soc/qcom/cmd-db.c:cmd_db_read_slave_id
  - drivers/soc/qcom/cmd-db.c:cmd_db_read_aux_data
  - drivers/soc/qcom/cmd-db.c:cmd_db_read_addr
```
**Symbols:**

```
c0937b4c-c0937c7c: cmd_db_get_header (STB_LOCAL)
```
</details>
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
