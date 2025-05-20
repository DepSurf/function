# Function: <code>espintcp_tx_work</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void espintcp_tx_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b22de0)
Location: net/xfrm/espintcp.c:401
Inline: False
```
**Symbols:**

```
ffffffff81b22de0-ffffffff81b22e2a: espintcp_tx_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void espintcp_tx_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b317d0)
Location: net/xfrm/espintcp.c:405
Inline: False
```
**Symbols:**

```
ffffffff81b317d0-ffffffff81b3181a: espintcp_tx_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void espintcp_tx_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/espintcp.c (ffffffff81b1f500)
Location: net/xfrm/espintcp.c:405
Inline: False
```
**Symbols:**

```
ffffffff81b1f500-ffffffff81b1f54a: espintcp_tx_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void espintcp_tx_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/espintcp.c (0)
Location: net/xfrm/espintcp.c:405
Inline: False
```
**Symbols:**

```
ffffffff81be4510-ffffffff81be4566: espintcp_tx_work (STB_LOCAL)
ffffffff81d3efd7-ffffffff81d3efeb: espintcp_tx_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void espintcp_tx_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/espintcp.c (0)
Location: net/xfrm/espintcp.c:403
Inline: False
```
**Symbols:**

```
ffffffff81d7baf0-ffffffff81d7bb5a: espintcp_tx_work (STB_LOCAL)
ffffffff81f0b933-ffffffff81f0b947: espintcp_tx_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void espintcp_tx_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/espintcp.c (0)
Location: net/xfrm/espintcp.c:403
Inline: False
```
**Symbols:**

```
ffffffff81f48bb0-ffffffff81f48c1a: espintcp_tx_work (STB_LOCAL)
ffffffff820b318c-ffffffff820b31a0: espintcp_tx_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void espintcp_tx_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/espintcp.c (0)
Location: net/xfrm/espintcp.c:412
Inline: False
```
**Symbols:**

```
ffffffff81fa8a20-ffffffff81fa8a8a: espintcp_tx_work (STB_LOCAL)
ffffffff8213438a-ffffffff8213439e: espintcp_tx_work.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void espintcp_tx_work(struct work_struct *work);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/espintcp.c (0)
Location: net/xfrm/espintcp.c:412
Inline: False
```
**Symbols:**

```
ffffffff82075d10-ffffffff82075d7a: espintcp_tx_work (STB_LOCAL)
ffffffff82215f53-ffffffff82215f67: espintcp_tx_work.cold (STB_LOCAL)
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
