# Function: <code>cec_s_conn_info</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void cec_s_conn_info(struct cec_adapter *adap, const struct cec_connector_info *conn_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81846000)
Location: drivers/media/cec/cec-adap.c:1614
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff81846000-ffffffff818460f1: cec_s_conn_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void cec_s_conn_info(struct cec_adapter *adap, const struct cec_connector_info *conn_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81877930)
Location: drivers/media/cec/cec-adap.c:1628
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff81877930-ffffffff81877a3b: cec_s_conn_info (STB_GLOBAL)
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void cec_s_conn_info(struct cec_adapter *adap, const struct cec_connector_info *conn_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffff800010abf440)
Location: drivers/media/cec/cec-adap.c:1628
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffff800010abf440-ffff800010abf4f4: cec_s_conn_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void cec_s_conn_info(struct cec_adapter *adap, const struct cec_connector_info *conn_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c0ba1134)
Location: drivers/media/cec/cec-adap.c:1628
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
c0ba1134-c0ba11a8: cec_s_conn_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void cec_s_conn_info(struct cec_adapter *adap, const struct cec_connector_info *conn_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (c000000000ba0e90)
Location: drivers/media/cec/cec-adap.c:1628
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
c000000000ba0e90-c000000000ba0f64: cec_s_conn_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void cec_s_conn_info(struct cec_adapter *adap, const struct cec_connector_info *conn_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffe0006c0dae)
Location: drivers/media/cec/cec-adap.c:1628
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffe0006c0dae-ffffffe0006c0e40: cec_s_conn_info (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void cec_s_conn_info(struct cec_adapter *adap, const struct cec_connector_info *conn_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8181fea0)
Location: drivers/media/cec/cec-adap.c:1628
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff8181fea0-ffffffff8181ffab: cec_s_conn_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void cec_s_conn_info(struct cec_adapter *adap, const struct cec_connector_info *conn_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff817e7540)
Location: drivers/media/cec/cec-adap.c:1628
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff817e7540-ffffffff817e764b: cec_s_conn_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void cec_s_conn_info(struct cec_adapter *adap, const struct cec_connector_info *conn_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff8186cde0)
Location: drivers/media/cec/cec-adap.c:1628
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff8186cde0-ffffffff8186ceeb: cec_s_conn_info (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void cec_s_conn_info(struct cec_adapter *adap, const struct cec_connector_info *conn_info);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/media/cec/cec-adap.c (ffffffff81886d70)
Location: drivers/media/cec/cec-adap.c:1628
Inline: True
Direct callers:
  - drivers/media/cec/cec-notifier.c:cec_notifier_conn_register
```
**Symbols:**

```
ffffffff81886d70-ffffffff81886e7b: cec_s_conn_info (STB_GLOBAL)
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
