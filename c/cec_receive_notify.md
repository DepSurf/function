# Function: <code>cec_receive_notify</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81805668)
Location: drivers/media/cec/cec-adap.c:1812
Inline: True
Inline callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int cec_receive_notify(struct cec_adapter *adap, struct cec_msg *msg, bool is_reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1873
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
ffffffff81846f20-ffffffff81847525: cec_receive_notify (STB_LOCAL)
ffffffff81848b6a-ffffffff81848be2: cec_receive_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int cec_receive_notify(struct cec_adapter *adap, struct cec_msg *msg, bool is_reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1890
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
ffffffff81878870-ffffffff81878e75: cec_receive_notify (STB_LOCAL)
ffffffff8187a397-ffffffff8187a40f: cec_receive_notify.cold (STB_LOCAL)
```
</details>
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
int cec_receive_notify(struct cec_adapter *adap, struct cec_msg *msg, bool is_reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010ac0430)
Location: drivers/media/cec/cec-adap.c:1890
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
ffff800010ac0430-ffff800010ac09d4: cec_receive_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cec_receive_notify(struct cec_adapter *adap, struct cec_msg *msg, bool is_reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba20f4)
Location: drivers/media/cec/cec-adap.c:1890
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
c0ba20f4-c0ba27e4: cec_receive_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cec_receive_notify(struct cec_adapter *adap, struct cec_msg *msg, bool is_reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba2370)
Location: drivers/media/cec/cec-adap.c:1890
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
c000000000ba2370-c000000000ba2c0c: cec_receive_notify (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cec_receive_notify(struct cec_adapter *adap, struct cec_msg *msg, bool is_reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c1b0a)
Location: drivers/media/cec/cec-adap.c:1890
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
ffffffe0006c1b0a-ffffffe0006c2060: cec_receive_notify (STB_LOCAL)
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
int cec_receive_notify(struct cec_adapter *adap, struct cec_msg *msg, bool is_reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1890
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
ffffffff81820de0-ffffffff818213e5: cec_receive_notify (STB_LOCAL)
ffffffff81822907-ffffffff8182297f: cec_receive_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int cec_receive_notify(struct cec_adapter *adap, struct cec_msg *msg, bool is_reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1890
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
ffffffff817e8480-ffffffff817e8a85: cec_receive_notify (STB_LOCAL)
ffffffff817e9fa7-ffffffff817ea01f: cec_receive_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int cec_receive_notify(struct cec_adapter *adap, struct cec_msg *msg, bool is_reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1890
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
ffffffff8186dd20-ffffffff8186e325: cec_receive_notify (STB_LOCAL)
ffffffff8186f847-ffffffff8186f8bf: cec_receive_notify.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int cec_receive_notify(struct cec_adapter *adap, struct cec_msg *msg, bool is_reply);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/media/cec/cec-adap.c (0)
Location: drivers/media/cec/cec-adap.c:1890
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
ffffffff81887ca0-ffffffff818882a5: cec_receive_notify (STB_LOCAL)
ffffffff818897c7-ffffffff8188983f: cec_receive_notify.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
