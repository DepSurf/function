# Function: <code>cec_feature_abort_reason</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
int cec_feature_abort_reason(struct cec_adapter *adap, struct cec_msg *msg, u8 reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81805370)
Location: drivers/media/cec/cec-adap.c:1774
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
ffffffff81805370-ffffffff818053f0: cec_feature_abort_reason (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cec_feature_abort_reason(struct cec_adapter *adap, struct cec_msg *msg, u8 reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81846e90)
Location: drivers/media/cec/cec-adap.c:1835
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
**Symbols:**

```
ffffffff81846e90-ffffffff81846f19: cec_feature_abort_reason (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cec_feature_abort_reason(struct cec_adapter *adap, struct cec_msg *msg, u8 reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff818787e0)
Location: drivers/media/cec/cec-adap.c:1852
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
**Symbols:**

```
ffffffff818787e0-ffffffff81878869: cec_feature_abort_reason (STB_LOCAL)
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
int cec_feature_abort_reason(struct cec_adapter *adap, struct cec_msg *msg, u8 reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010ac0378)
Location: drivers/media/cec/cec-adap.c:1852
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
**Symbols:**

```
ffff800010ac0378-ffff800010ac0430: cec_feature_abort_reason (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cec_feature_abort_reason(struct cec_adapter *adap, struct cec_msg *msg, u8 reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba202c)
Location: drivers/media/cec/cec-adap.c:1852
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
**Symbols:**

```
c0ba202c-c0ba20f4: cec_feature_abort_reason (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cec_feature_abort_reason(struct cec_adapter *adap, struct cec_msg *msg, u8 reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba2290)
Location: drivers/media/cec/cec-adap.c:1852
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
**Symbols:**

```
c000000000ba2290-c000000000ba2368: cec_feature_abort_reason (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cec_feature_abort_reason(struct cec_adapter *adap, struct cec_msg *msg, u8 reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c1a7c)
Location: drivers/media/cec/cec-adap.c:1852
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
**Symbols:**

```
ffffffe0006c1a7c-ffffffe0006c1b0a: cec_feature_abort_reason (STB_LOCAL)
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
int cec_feature_abort_reason(struct cec_adapter *adap, struct cec_msg *msg, u8 reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81820d50)
Location: drivers/media/cec/cec-adap.c:1852
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
**Symbols:**

```
ffffffff81820d50-ffffffff81820dd9: cec_feature_abort_reason (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cec_feature_abort_reason(struct cec_adapter *adap, struct cec_msg *msg, u8 reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e83f0)
Location: drivers/media/cec/cec-adap.c:1852
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
**Symbols:**

```
ffffffff817e83f0-ffffffff817e8479: cec_feature_abort_reason (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cec_feature_abort_reason(struct cec_adapter *adap, struct cec_msg *msg, u8 reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186dc90)
Location: drivers/media/cec/cec-adap.c:1852
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
**Symbols:**

```
ffffffff8186dc90-ffffffff8186dd19: cec_feature_abort_reason (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cec_feature_abort_reason(struct cec_adapter *adap, struct cec_msg *msg, u8 reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81887c10)
Location: drivers/media/cec/cec-adap.c:1852
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
```
**Symbols:**

```
ffffffff81887c10-ffffffff81887c99: cec_feature_abort_reason (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
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
