# Function: <code>ethnl_init_reply_data</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81a866f9)
Location: net/ethtool/netlink.c:299
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
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
In net/ethtool/netlink.c (ffffffff81a90009)
Location: net/ethtool/netlink.c:300
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_doit
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
In net/ethtool/netlink.c (ffffffff81a79729)
Location: net/ethtool/netlink.c:303
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
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
In net/ethtool/netlink.c (ffffffff81b33aaa)
Location: net/ethtool/netlink.c:338
Inline: True
Inline callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81cbe170)
Location: net/ethtool/netlink.c:341
Inline: True
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81cbe170-ffffffff81cbe19b: ethnl_init_reply_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81e7cc00)
Location: net/ethtool/netlink.c:343
Inline: True
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81e7cc00-ffffffff81e7cc2b: ethnl_init_reply_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81ed8fc0)
Location: net/ethtool/netlink.c:363
Inline: True
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81ed8fc0-ffffffff81ed8feb: ethnl_init_reply_data.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ethtool/netlink.c (ffffffff81f9ce70)
Location: net/ethtool/netlink.c:361
Inline: True
Direct callers:
  - net/ethtool/netlink.c:ethnl_default_notify
  - net/ethtool/netlink.c:ethnl_default_dumpit
  - net/ethtool/netlink.c:ethnl_default_doit
```
**Symbols:**

```
ffffffff81f9ce70-ffffffff81f9ce9b: ethnl_init_reply_data.isra.0 (STB_LOCAL)
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
