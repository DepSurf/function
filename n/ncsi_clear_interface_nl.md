# Function: <code>ncsi_clear_interface_nl</code>

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
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff819ca860)
Location: net/ncsi/ncsi-netlink.c:339
Inline: False
```
**Symbols:**

```
ffffffff819ca860-ffffffff819ca908: ncsi_clear_interface_nl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81a02ec0)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffffffff81a02ec0-ffffffff81a02fd0: ncsi_clear_interface_nl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffffffff81a72200-ffffffff81a722dd: ncsi_clear_interface_nl (STB_LOCAL)
ffffffff81a73754-ffffffff81a73783: ncsi_clear_interface_nl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffffffff81aa89c0-ffffffff81aa8a9d: ncsi_clear_interface_nl (STB_LOCAL)
ffffffff81aa9f44-ffffffff81aa9f73: ncsi_clear_interface_nl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffffffff81ba4d90-ffffffff81ba4efe: ncsi_clear_interface_nl (STB_LOCAL)
ffffffff81ba61fd-ffffffff81ba6245: ncsi_clear_interface_nl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffffffff81bb4250-ffffffff81bb43c4: ncsi_clear_interface_nl (STB_LOCAL)
ffffffff81c33cec-ffffffff81c33d34: ncsi_clear_interface_nl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffffffff81ba3230-ffffffff81ba33a0: ncsi_clear_interface_nl (STB_LOCAL)
ffffffff81c2605f-ffffffff81c260a7: ncsi_clear_interface_nl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:356
Inline: False
```
**Symbols:**

```
ffffffff81c70a40-ffffffff81c70bb0: ncsi_clear_interface_nl (STB_LOCAL)
ffffffff81d42d0d-ffffffff81d42d55: ncsi_clear_interface_nl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:356
Inline: False
```
**Symbols:**

```
ffffffff81e14660-ffffffff81e147d2: ncsi_clear_interface_nl (STB_LOCAL)
ffffffff81f0f6a4-ffffffff81f0f6f0: ncsi_clear_interface_nl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff81feb490)
Location: net/ncsi/ncsi-netlink.c:356
Inline: False
```
**Symbols:**

```
ffffffff81feb490-ffffffff81feb627: ncsi_clear_interface_nl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff82067730)
Location: net/ncsi/ncsi-netlink.c:356
Inline: False
```
**Symbols:**

```
ffffffff82067730-ffffffff820678c7: ncsi_clear_interface_nl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffff8213a9b0)
Location: net/ncsi/ncsi-netlink.c:356
Inline: False
```
**Symbols:**

```
ffffffff8213a9b0-ffffffff8213ab47: ncsi_clear_interface_nl (STB_LOCAL)
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
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffff800010d7c3a8)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffff800010d7c3a8-ffff800010d7c5ac: ncsi_clear_interface_nl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (c0e77448)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
c0e77448-c0e77560: ncsi_clear_interface_nl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (c000000000ebbd50)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
c000000000ebbd50-c000000000ebbef8: ncsi_clear_interface_nl (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-netlink.c (ffffffe0008aa446)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffffffe0008aa446-ffffffe0008aa544: ncsi_clear_interface_nl (STB_LOCAL)
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
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffffffff81a47d50-ffffffff81a47e2d: ncsi_clear_interface_nl (STB_LOCAL)
ffffffff81a492d4-ffffffff81a49303: ncsi_clear_interface_nl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffffffff81a04940-ffffffff81a04a1d: ncsi_clear_interface_nl (STB_LOCAL)
ffffffff81a05ec4-ffffffff81a05ef3: ncsi_clear_interface_nl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffffffff81ab3c00-ffffffff81ab3cdd: ncsi_clear_interface_nl (STB_LOCAL)
ffffffff81ab5184-ffffffff81ab51b3: ncsi_clear_interface_nl.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int ncsi_clear_interface_nl(struct sk_buff *msg, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-netlink.c (0)
Location: net/ncsi/ncsi-netlink.c:352
Inline: False
```
**Symbols:**

```
ffffffff81abffa0-ffffffff81ac007d: ncsi_clear_interface_nl (STB_LOCAL)
ffffffff81ac1524-ffffffff81ac1553: ncsi_clear_interface_nl.cold (STB_LOCAL)
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
