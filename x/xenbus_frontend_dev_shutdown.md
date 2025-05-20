# Function: <code>xenbus_frontend_dev_shutdown</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void xenbus_frontend_dev_shutdown(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:128
Inline: False
```
**Symbols:**

```
ffffffff817208b0-ffffffff8172095b: xenbus_frontend_dev_shutdown (STB_LOCAL)
ffffffff81721205-ffffffff81721222: xenbus_frontend_dev_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void xenbus_frontend_dev_shutdown(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:128
Inline: False
```
**Symbols:**

```
ffffffff8173d810-ffffffff8173d8bb: xenbus_frontend_dev_shutdown (STB_LOCAL)
ffffffff81c0578e-ffffffff81c057ab: xenbus_frontend_dev_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void xenbus_frontend_dev_shutdown(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:128
Inline: False
```
**Symbols:**

```
ffffffff81721390-ffffffff8172143b: xenbus_frontend_dev_shutdown (STB_LOCAL)
ffffffff81bf7429-ffffffff81bf7446: xenbus_frontend_dev_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void xenbus_frontend_dev_shutdown(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:128
Inline: False
```
**Symbols:**

```
ffffffff817a01b0-ffffffff817a0258: xenbus_frontend_dev_shutdown (STB_LOCAL)
ffffffff81cf6328-ffffffff81cf6345: xenbus_frontend_dev_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void xenbus_frontend_dev_shutdown(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (0)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:128
Inline: False
```
**Symbols:**

```
ffffffff818d9c80-ffffffff818d9d33: xenbus_frontend_dev_shutdown (STB_LOCAL)
ffffffff81ebe432-ffffffff81ebe44e: xenbus_frontend_dev_shutdown.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xenbus_frontend_dev_shutdown(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a2c790)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:128
Inline: False
```
**Symbols:**

```
ffffffff81a2c790-ffffffff81a2c872: xenbus_frontend_dev_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xenbus_frontend_dev_shutdown(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81a75f40)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:128
Inline: False
```
**Symbols:**

```
ffffffff81a75f40-ffffffff81a76022: xenbus_frontend_dev_shutdown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xenbus_frontend_dev_shutdown(struct device *_dev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/xen/xenbus/xenbus_probe_frontend.c (ffffffff81ac8130)
Location: drivers/xen/xenbus/xenbus_probe_frontend.c:128
Inline: False
```
**Symbols:**

```
ffffffff81ac8130-ffffffff81ac8212: xenbus_frontend_dev_shutdown (STB_LOCAL)
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
