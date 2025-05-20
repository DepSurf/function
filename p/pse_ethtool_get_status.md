# Function: <code>pse_ethtool_get_status</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pse_ethtool_get_status(struct pse_control *psec, struct netlink_ext_ack *extack, struct pse_control_status *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/pse-pd/pse_core.c (ffffffff81bea050)
Location: drivers/net/pse-pd/pse_core.c:264
Inline: False
Direct callers:
  - net/ethtool/pse-pd.c:pse_prepare_data
```
**Symbols:**

```
ffffffff81bea050-ffffffff81bea0dc: pse_ethtool_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pse_ethtool_get_status(struct pse_control *psec, struct netlink_ext_ack *extack, struct pse_control_status *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/pse-pd/pse_core.c (ffffffff81c42480)
Location: drivers/net/pse-pd/pse_core.c:264
Inline: False
Direct callers:
  - net/ethtool/pse-pd.c:pse_prepare_data
```
**Symbols:**

```
ffffffff81c42480-ffffffff81c4250c: pse_ethtool_get_status (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pse_ethtool_get_status(struct pse_control *psec, struct netlink_ext_ack *extack, struct pse_control_status *status);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/pse-pd/pse_core.c (ffffffff81cf7b40)
Location: drivers/net/pse-pd/pse_core.c:264
Inline: False
Direct callers:
  - net/ethtool/pse-pd.c:pse_prepare_data
```
**Symbols:**

```
ffffffff81cf7b40-ffffffff81cf7bcc: pse_ethtool_get_status (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
