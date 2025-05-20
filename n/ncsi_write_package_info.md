# Function: <code>ncsi_write_package_info</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff819cab00)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff819cab00-ffffffff819caf62: ncsi_write_package_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81a035b0)
Location: net/ncsi/ncsi-netlink.c:98
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81a035b0-ffffffff81a03a22: ncsi_write_package_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81a72820-ffffffff81a72cdd: ncsi_write_package_info (STB_LOCAL)
ffffffff81a73866-ffffffff81a73923: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81aa8fe0-ffffffff81aa94b2: ncsi_write_package_info (STB_LOCAL)
ffffffff81aaa056-ffffffff81aaa077: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81ba4a50-ffffffff81ba4d90: ncsi_write_package_info (STB_LOCAL)
ffffffff81ba61dc-ffffffff81ba61fd: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81bb3f10-ffffffff81bb4250: ncsi_write_package_info (STB_LOCAL)
ffffffff81c33ccb-ffffffff81c33cec: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81ba2ef0-ffffffff81ba3224: ncsi_write_package_info (STB_LOCAL)
ffffffff81c2603e-ffffffff81c2605f: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81c712d0-ffffffff81c7163e: ncsi_write_package_info (STB_LOCAL)
ffffffff81d42ea0-ffffffff81d42ee1: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81e14e90-ffffffff81e151d9: ncsi_write_package_info (STB_LOCAL)
ffffffff81f0f829-ffffffff81f0f865: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81febdd0-ffffffff81fec129: ncsi_write_package_info (STB_LOCAL)
ffffffff820b5c76-ffffffff820b5c96: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff82068070-ffffffff820683c9: ncsi_write_package_info (STB_LOCAL)
ffffffff821371d7-ffffffff821371f7: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff8213b2f0-ffffffff8213b649: ncsi_write_package_info (STB_LOCAL)
ffffffff82219039-ffffffff82219059: ncsi_write_package_info.cold (STB_LOCAL)
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
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffff800010d7ca40)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffff800010d7ca40-ffff800010d7cf2c: ncsi_write_package_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (c0e778d8)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
c0e778d8-c0e77d38: ncsi_write_package_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (c000000000ebc3d0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
c000000000ebc3d0-c000000000ebca9c: ncsi_write_package_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffe0008aa834)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffe0008aa834-ffffffe0008aabaa: ncsi_write_package_info (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81a48370-ffffffff81a48842: ncsi_write_package_info (STB_LOCAL)
ffffffff81a493e6-ffffffff81a49407: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81a04f60-ffffffff81a05432: ncsi_write_package_info (STB_LOCAL)
ffffffff81a05fd6-ffffffff81a05ff7: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81ab4220-ffffffff81ab46f2: ncsi_write_package_info (STB_LOCAL)
ffffffff81ab5296-ffffffff81ab52b7: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ncsi_write_package_info(struct sk_buff *skb, struct ncsi_dev_priv *ndp, unsigned int id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:94
Inline: False
Direct callers:
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_all_nl
  - net/ncsi/ncsi-netlink.c:ncsi_pkg_info_nl
```
**Symbols:**

```
ffffffff81ac05c0-ffffffff81ac0a92: ncsi_write_package_info (STB_LOCAL)
ffffffff81ac1636-ffffffff81ac1657: ncsi_write_package_info.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
