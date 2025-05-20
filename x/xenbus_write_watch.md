# Function: <code>xenbus_write_watch</code>

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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff814d074f)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:363
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815214d6)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:365
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8154d916)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:388
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815619a1)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:454
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c5fc7)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:454
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815fe8c0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:463
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8161998f)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:463
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164d6a4)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:481
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166fba0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
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
int xenbus_write_watch(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171ffa0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff8171ffa0-ffffffff8172018b: xenbus_write_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xenbus_write_watch(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173cf00)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff8173cf00-ffffffff8173d0eb: xenbus_write_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xenbus_write_watch(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81720a70)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff81720a70-ffffffff81720c5b: xenbus_write_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xenbus_write_watch(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179f890)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff8179f890-ffffffff8179fa7b: xenbus_write_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xenbus_write_watch(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d9320)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff818d9320-ffffffff818d9523: xenbus_write_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xenbus_write_watch(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2bdd0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff81a2bdd0-ffffffff81a2bfd3: xenbus_write_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xenbus_write_watch(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a75570)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff81a75570-ffffffff81a75773: xenbus_write_watch (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xenbus_write_watch(unsigned int msg_type, struct xenbus_file_priv *u);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac7730)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
```
**Symbols:**

```
ffffffff81ac7730-ffffffff81ac7962: xenbus_write_watch (STB_LOCAL)
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff80001083aaa4)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635c60)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff816639e0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
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
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167dfa0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:496
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
