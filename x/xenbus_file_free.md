# Function: <code>xenbus_file_free</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void xenbus_file_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81561400)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:300
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
**Symbols:**

```
ffffffff81561400-ffffffff81561557: xenbus_file_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void xenbus_file_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815c56f0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:300
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
**Symbols:**

```
ffffffff815c56f0-ffffffff815c5847: xenbus_file_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void xenbus_file_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff815fdde0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:300
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
**Symbols:**

```
ffffffff815fdde0-ffffffff815fdf37: xenbus_file_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void xenbus_file_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81618eb0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:300
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
**Symbols:**

```
ffffffff81618eb0-ffffffff81619007: xenbus_file_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void xenbus_file_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8164cbc0)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:303
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
**Symbols:**

```
ffffffff8164cbc0-ffffffff8164cd06: xenbus_file_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void xenbus_file_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8166f050)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
**Symbols:**

```
ffffffff8166f050-ffffffff8166f070: xenbus_file_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8171f9aa)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8173c90a)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8172046a)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8179f28a)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff818d8ea4)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a2b924)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81a750c4)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81ac7254)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: True
Inline callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
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
void xenbus_file_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffff800010839e20)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
**Symbols:**

```
ffff800010839e20-ffff800010839e58: xenbus_file_free (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
void xenbus_file_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81635110)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
**Symbols:**

```
ffffffff81635110-ffffffff81635130: xenbus_file_free (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void xenbus_file_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff81662e90)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
**Symbols:**

```
ffffffff81662e90-ffffffff81662eb0: xenbus_file_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void xenbus_file_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_dev_frontend.c (ffffffff8167d460)
Location: drivers/xen/xenbus/xenbus_dev_frontend.c:339
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_release
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_file_write
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_command_reply
  - drivers/xen/xenbus/xenbus_dev_frontend.c:xenbus_dev_queue_reply
```
**Symbols:**

```
ffffffff8167d460-ffffffff8167d480: xenbus_file_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
