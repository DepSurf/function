# Function: <code>fec_prepare_data</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fec_prepare_data(const struct ethnl_req_info *req_base, struct ethnl_reply_data *reply_base, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81a81610)
Location: net/ethtool/fec.c:93
Inline: False
```
**Symbols:**

```
ffffffff81a81610-ffffffff81a8184a: fec_prepare_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fec_prepare_data(const struct ethnl_req_info *req_base, struct ethnl_reply_data *reply_base, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81b3b390)
Location: net/ethtool/fec.c:93
Inline: False
```
**Symbols:**

```
ffffffff81b3b390-ffffffff81b3b56a: fec_prepare_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fec_prepare_data(const struct ethnl_req_info *req_base, struct ethnl_reply_data *reply_base, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81cc7380)
Location: net/ethtool/fec.c:93
Inline: False
```
**Symbols:**

```
ffffffff81cc7380-ffffffff81cc7569: fec_prepare_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fec_prepare_data(const struct ethnl_req_info *req_base, struct ethnl_reply_data *reply_base, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81e86a20)
Location: net/ethtool/fec.c:93
Inline: False
```
**Symbols:**

```
ffffffff81e86a20-ffffffff81e86bcc: fec_prepare_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fec_prepare_data(const struct ethnl_req_info *req_base, struct ethnl_reply_data *reply_base, struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81ee3780)
Location: net/ethtool/fec.c:93
Inline: False
```
**Symbols:**

```
ffffffff81ee3780-ffffffff81ee392c: fec_prepare_data (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fec_prepare_data(const struct ethnl_req_info *req_base, struct ethnl_reply_data *reply_base, const struct genl_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ethtool/fec.c (ffffffff81fa7560)
Location: net/ethtool/fec.c:93
Inline: False
```
**Symbols:**

```
ffffffff81fa7560-ffffffff81fa770c: fec_prepare_data (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct genl_info *info</code> ➡️ <code>const struct genl_info *info</code>
</li>
</ul>
</details>
</li>
</ul>
