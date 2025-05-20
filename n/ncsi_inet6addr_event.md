# Function: <code>ncsi_inet6addr_event</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ncsi_inet6addr_event(struct notifier_block *this, long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8188e340)
Location: net/ncsi/ncsi-manage.c:1029
Inline: False
```
**Symbols:**

```
ffffffff8188e340-ffffffff8188e499: ncsi_inet6addr_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ncsi_inet6addr_event(struct notifier_block *this, long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818c2620)
Location: net/ncsi/ncsi-manage.c:1131
Inline: False
```
**Symbols:**

```
ffffffff818c2620-ffffffff818c2783: ncsi_inet6addr_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ncsi_inet6addr_event(struct notifier_block *this, long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff818e8fb0)
Location: net/ncsi/ncsi-manage.c:1131
Inline: False
```
**Symbols:**

```
ffffffff818e8fb0-ffffffff818e9113: ncsi_inet6addr_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ncsi_inet6addr_event(struct notifier_block *this, long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff8196e520)
Location: net/ncsi/ncsi-manage.c:1341
Inline: False
```
**Symbols:**

```
ffffffff8196e520-ffffffff8196e683: ncsi_inet6addr_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ncsi_inet6addr_event(struct notifier_block *this, long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819c7f70)
Location: net/ncsi/ncsi-manage.c:1233
Inline: False
```
**Symbols:**

```
ffffffff819c7f70-ffffffff819c80d3: ncsi_inet6addr_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ncsi_inet6addr_event(struct notifier_block *this, long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ncsi/ncsi-manage.c (ffffffff819ffbd0)
Location: net/ncsi/ncsi-manage.c:1491
Inline: False
```
**Symbols:**

```
ffffffff819ffbd0-ffffffff819ffd33: ncsi_inet6addr_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int ncsi_inet6addr_event(struct notifier_block *this, long unsigned int event, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ncsi/ncsi-manage.c (0)
Location: net/ncsi/ncsi-manage.c:1487
Inline: False
```
**Symbols:**

```
ffffffff81a6eec0-ffffffff81a6eff7: ncsi_inet6addr_event (STB_LOCAL)
ffffffff81a71de0-ffffffff81a71e0c: ncsi_inet6addr_event.cold (STB_LOCAL)
```
</details>
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
</ul>
