# Function: <code>xenbus_write_transaction</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff814d08b4)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:305
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815213d2)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:305
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8154da2c)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:328
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81561ab2)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:427
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c60d8)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:427
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815fe767)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:428
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81619837)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:428
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164d559)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:431
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166fa52)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xenbus_write_transaction(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171fd70)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff8171fd70-ffffffff8171ff9c: xenbus_write_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xenbus_write_transaction(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173ccd0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff8173ccd0-ffffffff8173cefc: xenbus_write_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenbus_write_transaction(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81720840)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff81720840-ffffffff81720a6c: xenbus_write_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenbus_write_transaction(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179f660)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff8179f660-ffffffff8179f88c: xenbus_write_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenbus_write_transaction(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d90d0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff818d90d0-ffffffff818d931d: xenbus_write_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_write_transaction(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2bb70)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff81a2bb70-ffffffff81a2bdbd: xenbus_write_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_write_transaction(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a75310)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff81a75310-ffffffff81a7555d: xenbus_write_transaction (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_write_transaction(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac74a0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff81ac74a0-ffffffff81ac771c: xenbus_write_transaction (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083aa04)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635b12)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81663892)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167de52)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:446
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
</details>
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
