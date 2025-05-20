# Function: <code>xs_single</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff814cd470)
Location: drivers/xen/xenbus/xenbus_xs.c:323
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
```
**Symbols:**

```
ffffffff814cd470-ffffffff814cd4e2: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8151dff0)
Location: drivers/xen/xenbus/xenbus_xs.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8151dff0-ffffffff8151e062: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8154a470)
Location: drivers/xen/xenbus/xenbus_xs.c:318
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8154a470-ffffffff8154a4e2: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8155ec90)
Location: drivers/xen/xenbus/xenbus_xs.c:344
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8155ec90-ffffffff8155ed02: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815c2fc0)
Location: drivers/xen/xenbus/xenbus_xs.c:347
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff815c2fc0-ffffffff815c3032: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff815fb660)
Location: drivers/xen/xenbus/xenbus_xs.c:349
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff815fb660-ffffffff815fb6d2: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81616710)
Location: drivers/xen/xenbus/xenbus_xs.c:349
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81616710-ffffffff81616782: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8164a3c0)
Location: drivers/xen/xenbus/xenbus_xs.c:352
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8164a3c0-ffffffff8164a434: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8166c850)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8166c850-ffffffff8166c8c4: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171c9e0)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_reset_watches
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8171c9e0-ffffffff8171ca54: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff817399a0)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_reset_watches
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff817399a0-ffffffff81739a14: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8171d2d0)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8171d2d0-ffffffff8171d344: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8179c080)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8179c080-ffffffff8179c0f4: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff818d56d0)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff818d56d0-ffffffff818d5751: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a27ab0)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81a27ab0-ffffffff81a27b31: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81a711b0)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81a711b0-ffffffff81a71231: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81ac3310)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_gather
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_scanf
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81ac3310-ffffffff81ac3391: xs_single (STB_LOCAL)
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
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffff800010836ec8)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffff800010836ec8-ffff800010836f5c: xs_single (STB_LOCAL)
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
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff816326c0)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff816326c0-ffffffff81632734: xs_single (STB_LOCAL)
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
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff81660690)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff81660690-ffffffff81660704: xs_single (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *xs_single(struct xenbus_transaction t, enum xsd_sockmsg_type type, const char *string, unsigned int *len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_xs.c (ffffffff8167ac70)
Location: drivers/xen/xenbus/xenbus_xs.c:355
Inline: False
Direct callers:
  - drivers/xen/xenbus/xenbus_xs.c:xs_init
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_end
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_transaction_start
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_rm
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_mkdir
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_read
  - drivers/xen/xenbus/xenbus_xs.c:xenbus_directory
```
**Symbols:**

```
ffffffff8167ac70-ffffffff8167ace4: xs_single (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
