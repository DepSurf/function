# Function: <code>dcbnl_netdevice_event</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int dcbnl_netdevice_event(struct notifier_block *nb, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81c64c40)
Location: net/dcb/dcbnl.c:2092
Inline: False
```
**Symbols:**

```
ffffffff81c64c40-ffffffff81c64d04: dcbnl_netdevice_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dcbnl_netdevice_event(struct notifier_block *nb, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81e077d0)
Location: net/dcb/dcbnl.c:2092
Inline: False
```
**Symbols:**

```
ffffffff81e077d0-ffffffff81e078ac: dcbnl_netdevice_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dcbnl_netdevice_event(struct notifier_block *nb, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff81fdcb30)
Location: net/dcb/dcbnl.c:2235
Inline: False
```
**Symbols:**

```
ffffffff81fdcb30-ffffffff81fdcc0c: dcbnl_netdevice_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dcbnl_netdevice_event(struct notifier_block *nb, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff820589c0)
Location: net/dcb/dcbnl.c:2389
Inline: False
```
**Symbols:**

```
ffffffff820589c0-ffffffff82058a9c: dcbnl_netdevice_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dcbnl_netdevice_event(struct notifier_block *nb, long unsigned int event, void *ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/dcb/dcbnl.c (ffffffff8212b510)
Location: net/dcb/dcbnl.c:2389
Inline: False
```
**Symbols:**

```
ffffffff8212b510-ffffffff8212b5ec: dcbnl_netdevice_event (STB_LOCAL)
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
