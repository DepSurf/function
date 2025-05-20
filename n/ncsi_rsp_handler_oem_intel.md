# Function: <code>ncsi_rsp_handler_oem_intel</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ncsi_rsp_handler_oem_intel(struct ncsi_request *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:735
Inline: False
```
**Symbols:**

```
ffffffff81c6c520-ffffffff81c6c624: ncsi_rsp_handler_oem_intel (STB_LOCAL)
ffffffff81d423ca-ffffffff81d423e4: ncsi_rsp_handler_oem_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ncsi_rsp_handler_oem_intel(struct ncsi_request *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-rsp.c (0)
Location: net/ncsi/ncsi-rsp.c:735
Inline: False
```
**Symbols:**

```
ffffffff81e10480-ffffffff81e10596: ncsi_rsp_handler_oem_intel (STB_LOCAL)
ffffffff81f0edf8-ffffffff81f0ee12: ncsi_rsp_handler_oem_intel.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ncsi_rsp_handler_oem_intel(struct ncsi_request *nr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (ffffffff81fe6b70)
Location: net/ncsi/ncsi-rsp.c:735
Inline: False
```
**Symbols:**

```
ffffffff81fe6b70-ffffffff81fe6c9b: ncsi_rsp_handler_oem_intel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ncsi_rsp_handler_oem_intel(struct ncsi_request *nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (ffffffff82062c50)
Location: net/ncsi/ncsi-rsp.c:686
Inline: True
```
**Symbols:**

```
ffffffff82062c50-ffffffff82062c9d: ncsi_rsp_handler_oem_intel (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ncsi_rsp_handler_oem_intel(struct ncsi_request *nr);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-rsp.c (ffffffff82135d90)
Location: net/ncsi/ncsi-rsp.c:699
Inline: True
```
**Symbols:**

```
ffffffff82135d90-ffffffff82135ddd: ncsi_rsp_handler_oem_intel (STB_LOCAL)
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
