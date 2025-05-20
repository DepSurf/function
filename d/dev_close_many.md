# Function: <code>dev_close_many</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81714b80)
Location: net/core/dev.c:1437
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81714b80-ffffffff81714cba: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177cb90)
Location: net/core/dev.c:1441
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8177cb90-ffffffff8177ccc0: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817aa1d0)
Location: net/core/dev.c:1440
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff817aa1d0-ffffffff817aa300: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817c8830)
Location: net/core/dev.c:1474
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff817c8830-ffffffff817c8960: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818424d0)
Location: net/core/dev.c:1491
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818424d0-ffffffff81842607: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8188c8e0)
Location: net/core/dev.c:1492
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8188c8e0-ffffffff8188ca17: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818adb30)
Location: net/core/dev.c:1495
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818adb30-ffffffff818adc67: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818f9440)
Location: net/core/dev.c:1505
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818f9440-ffffffff818f9581: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192b5a0)
Location: net/core/dev.c:1423
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8192b5a0-ffffffff8192b6e1: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a00fd0)
Location: net/core/dev.c:1615
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81a00fd0-ffffffff81a010f9: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a01490)
Location: net/core/dev.c:1640
Inline: False
Direct callers:
  - net/core/dev.c:dev_change_net_namespace
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff81a01490-ffffffff81a015b9: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff819e7cc0)
Location: net/core/dev.c:1709
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff819e7cc0-ffffffff819e7ddd: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a98970)
Location: net/core/dev.c:1584
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff81a98970-ffffffff81a98a8d: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81c0e860)
Location: net/core/dev.c:1532
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff81c0e860-ffffffff81c0e98b: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81dbe940)
Location: net/core/dev.c:1517
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff81dbe940-ffffffff81dbea77: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81e38220)
Location: net/core/dev.c:1542
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff81e38220-ffffffff81e38357: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81ef6280)
Location: net/core/dev.c:1546
Inline: False
Direct callers:
  - net/core/dev.c:__dev_change_net_namespace
  - net/core/dev.c:unregister_netdevice_many_notify
```
**Symbols:**

```
ffffffff81ef6280-ffffffff81ef63ee: dev_close_many (STB_GLOBAL)
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
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcaed0)
Location: net/core/dev.c:1423
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffff800010bcaed0-ffff800010bcaff8: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce35d0)
Location: net/core/dev.c:1423
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
c0ce35d0-c0ce36f8: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca3840)
Location: net/core/dev.c:1423
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
c000000000ca3840-c000000000ca39c8: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000754380)
Location: net/core/dev.c:1423
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffe000754380-ffffffe000754464: dev_close_many (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cb5a0)
Location: net/core/dev.c:1423
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818cb5a0-ffffffff818cb6e1: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818854e0)
Location: net/core/dev.c:1423
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff818854e0-ffffffff81885621: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191c5a0)
Location: net/core/dev.c:1423
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8191c5a0-ffffffff8191c6e1: dev_close_many (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dev_close_many(struct list_head *head, bool unlink);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8193da70)
Location: net/core/dev.c:1423
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered_many
```
**Symbols:**

```
ffffffff8193da70-ffffffff8193dbb1: dev_close_many (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
