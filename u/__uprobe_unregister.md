# Function: <code>__uprobe_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81187ed0)
Location: kernel/events/uprobes.c:840
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81187ed0-ffffffff81187fd1: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8119a570)
Location: kernel/events/uprobes.c:842
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff8119a570-ffffffff8119a671: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811a9ce0)
Location: kernel/events/uprobes.c:843
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff811a9ce0-ffffffff811a9de1: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b1320)
Location: kernel/events/uprobes.c:851
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff811b1320-ffffffff811b1400: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c4f00)
Location: kernel/events/uprobes.c:851
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff811c4f00-ffffffff811c4fe0: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811e5450)
Location: kernel/events/uprobes.c:849
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff811e5450-ffffffff811e551c: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f5de0)
Location: kernel/events/uprobes.c:1060
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff811f5de0-ffffffff811f5eac: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/events/uprobes.c (0)
Location: kernel/events/uprobes.c:1048
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff8120db60-ffffffff8120dc2f: __uprobe_unregister (STB_LOCAL)
ffffffff8120f6cb-ffffffff8120f6f9: __uprobe_unregister.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121b190)
Location: kernel/events/uprobes.c:1100
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff8121b190-ffffffff8121b260: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81247a90)
Location: kernel/events/uprobes.c:1090
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81247a90-ffffffff81247b67: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81252160)
Location: kernel/events/uprobes.c:1090
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81252160-ffffffff81252237: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812560e0)
Location: kernel/events/uprobes.c:1088
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff812560e0-ffffffff812561b7: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81291d90)
Location: kernel/events/uprobes.c:1089
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81291d90-ffffffff81291e67: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e7570)
Location: kernel/events/uprobes.c:1083
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff812e7570-ffffffff812e764d: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813510a0)
Location: kernel/events/uprobes.c:1086
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff813510a0-ffffffff8135117d: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81382310)
Location: kernel/events/uprobes.c:1083
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81382310-ffffffff813823ed: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813ab6f0)
Location: kernel/events/uprobes.c:1083
Inline: False
Direct callers:
  - kernel/events/uprobes.c:__uprobe_register
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff813ab6f0-ffffffff813ab7cd: __uprobe_unregister (STB_LOCAL)
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
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a67f8)
Location: kernel/events/uprobes.c:1100
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffff8000102a67f8-ffff8000102a6934: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d5980)
Location: kernel/events/uprobes.c:1100
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
c04d5980-c04d5a98: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000359900)
Location: kernel/events/uprobes.c:1100
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
c000000000359900-c000000000359a84: __uprobe_unregister (STB_LOCAL)
```
</details>
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
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812137e0)
Location: kernel/events/uprobes.c:1100
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff812137e0-ffffffff812138b0: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81206550)
Location: kernel/events/uprobes.c:1100
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81206550-ffffffff81206620: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81211580)
Location: kernel/events/uprobes.c:1100
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff81211580-ffffffff81211650: __uprobe_unregister (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __uprobe_unregister(struct uprobe *uprobe, struct uprobe_consumer *uc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812204d0)
Location: kernel/events/uprobes.c:1100
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_unregister
```
**Symbols:**

```
ffffffff812204d0-ffffffff8122059e: __uprobe_unregister (STB_LOCAL)
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
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
