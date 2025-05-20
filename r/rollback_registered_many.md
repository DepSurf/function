# Function: <code>rollback_registered_many</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81716590)
Location: net/core/dev.c:6208
Inline: False
Direct callers:
  - net/core/dev.c:rollback_registered
  - net/core/dev.c:unregister_netdevice_many
```
**Symbols:**

```
ffffffff81716590-ffffffff817168c2: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8177e5e0)
Location: net/core/dev.c:6692
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff8177e5e0-ffffffff8177e91d: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817abde0)
Location: net/core/dev.c:6861
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_many
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff817abde0-ffffffff817ac20c: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff817ca390)
Location: net/core/dev.c:7059
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff817ca390-ffffffff817ca76b: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81843e90)
Location: net/core/dev.c:7231
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff81843e90-ffffffff81844264: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81897da0)
Location: net/core/dev.c:7424
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff81897da0-ffffffff818981a8: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818ba0e0)
Location: net/core/dev.c:8051
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff818ba0e0-ffffffff818ba605: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/dev.c (0)
Location: net/core/dev.c:8154
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff818fc5e0-ffffffff818fcacd: rollback_registered_many (STB_LOCAL)
ffffffff81907229-ffffffff8190729b: rollback_registered_many.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8192ebc0)
Location: net/core/dev.c:8465
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff8192ebc0-ffffffff8192f0d6: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a0d5e0)
Location: net/core/dev.c:8918
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff81a0d5e0-ffffffff81a0da95: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81a05890)
Location: net/core/dev.c:9532
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff81a05890-ffffffff81a05cbe: rollback_registered_many (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffff800010bcba08)
Location: net/core/dev.c:8465
Inline: False
Direct callers:
  - net/core/dev.c:unregister_netdevice_queue
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffff800010bcba08-ffff800010bcbf24: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c0ce9990)
Location: net/core/dev.c:8465
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
c0ce9990-c0ce9f98: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (c000000000ca8280)
Location: net/core/dev.c:8465
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
c000000000ca8280-c000000000ca8948: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffe000759362)
Location: net/core/dev.c:8465
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffe000759362-ffffffe0007597fa: rollback_registered_many (STB_LOCAL)
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
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff818cebc0)
Location: net/core/dev.c:8465
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff818cebc0-ffffffff818cf0d6: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81888ce0)
Location: net/core/dev.c:8465
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff81888ce0-ffffffff818891f6: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff8191fbc0)
Location: net/core/dev.c:8465
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff8191fbc0-ffffffff819200d6: rollback_registered_many (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rollback_registered_many(struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/dev.c (ffffffff81941920)
Location: net/core/dev.c:8465
Inline: False
Direct callers:
  - net/core/dev.c:register_netdevice
```
**Symbols:**

```
ffffffff81941920-ffffffff81941e36: rollback_registered_many (STB_LOCAL)
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
