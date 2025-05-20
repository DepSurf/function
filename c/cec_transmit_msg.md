# Function: <code>cec_transmit_msg</code>

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
int cec_transmit_msg(struct cec_adapter *adap, struct cec_msg *msg, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81805320)
Location: drivers/media/cec/cec-adap.c:867
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
  - drivers/media/cec/cec-adap.c:cec_received_msg_ts
```
**Symbols:**

```
ffffffff81805320-ffffffff8180536c: cec_transmit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int cec_transmit_msg(struct cec_adapter *adap, struct cec_msg *msg, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81846e40)
Location: drivers/media/cec/cec-adap.c:912
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
```
**Symbols:**

```
ffffffff81846e40-ffffffff81846e8e: cec_transmit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int cec_transmit_msg(struct cec_adapter *adap, struct cec_msg *msg, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81878790)
Location: drivers/media/cec/cec-adap.c:926
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
```
**Symbols:**

```
ffffffff81878790-ffffffff818787de: cec_transmit_msg (STB_GLOBAL)
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
int cec_transmit_msg(struct cec_adapter *adap, struct cec_msg *msg, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010ac0310)
Location: drivers/media/cec/cec-adap.c:926
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
```
**Symbols:**

```
ffff800010ac0310-ffff800010ac0374: cec_transmit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int cec_transmit_msg(struct cec_adapter *adap, struct cec_msg *msg, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba1fd8)
Location: drivers/media/cec/cec-adap.c:926
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
```
**Symbols:**

```
c0ba1fd8-c0ba202c: cec_transmit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int cec_transmit_msg(struct cec_adapter *adap, struct cec_msg *msg, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba2210)
Location: drivers/media/cec/cec-adap.c:926
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
```
**Symbols:**

```
c000000000ba2210-c000000000ba2290: cec_transmit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int cec_transmit_msg(struct cec_adapter *adap, struct cec_msg *msg, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c1a20)
Location: drivers/media/cec/cec-adap.c:926
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
```
**Symbols:**

```
ffffffe0006c1a20-ffffffe0006c1a7c: cec_transmit_msg (STB_GLOBAL)
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
int cec_transmit_msg(struct cec_adapter *adap, struct cec_msg *msg, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81820d00)
Location: drivers/media/cec/cec-adap.c:926
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
```
**Symbols:**

```
ffffffff81820d00-ffffffff81820d4e: cec_transmit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int cec_transmit_msg(struct cec_adapter *adap, struct cec_msg *msg, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e83a0)
Location: drivers/media/cec/cec-adap.c:926
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
```
**Symbols:**

```
ffffffff817e83a0-ffffffff817e83ee: cec_transmit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int cec_transmit_msg(struct cec_adapter *adap, struct cec_msg *msg, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186dc40)
Location: drivers/media/cec/cec-adap.c:926
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
```
**Symbols:**

```
ffffffff8186dc40-ffffffff8186dc8e: cec_transmit_msg (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int cec_transmit_msg(struct cec_adapter *adap, struct cec_msg *msg, bool block);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81887bc0)
Location: drivers/media/cec/cec-adap.c:926
Inline: False
Direct callers:
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_receive_notify
  - drivers/media/cec/cec-adap.c:cec_feature_abort_reason
```
**Symbols:**

```
ffffffff81887bc0-ffffffff81887c0e: cec_transmit_msg (STB_GLOBAL)
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
