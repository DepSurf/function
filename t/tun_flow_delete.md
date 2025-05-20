# Function: <code>tun_flow_delete</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff815edfc0)
Location: drivers/net/tun.c:309
Inline: True
Direct callers:
  - drivers/net/tun.c:tun_flow_flush
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:__tun_detach
```
**Symbols:**

```
ffffffff815edfc0-ffffffff815ee002: tun_flow_delete.isra.23 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8164d0b0)
Location: drivers/net/tun.c:324
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff8164d0b0-ffffffff8164d0f2: tun_flow_delete.isra.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8167edf0)
Location: drivers/net/tun.c:324
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff8167edf0-ffffffff8167ee32: tun_flow_delete.isra.36 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff816940d0)
Location: drivers/net/tun.c:326
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff816940d0-ffffffff81694112: tun_flow_delete.isra.39 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff816fe0d0)
Location: drivers/net/tun.c:406
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff816fe0d0-ffffffff816fe112: tun_flow_delete.isra.45 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8173c2d0)
Location: drivers/net/tun.c:443
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff8173c2d0-ffffffff8173c312: tun_flow_delete.isra.53 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8175fc10)
Location: drivers/net/tun.c:449
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff8175fc10-ffffffff8175fc52: tun_flow_delete.isra.51 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8179d320)
Location: drivers/net/tun.c:439
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff8179d320-ffffffff8179d367: tun_flow_delete.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817c0dc0)
Location: drivers/net/tun.c:439
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff817c0dc0-ffffffff817c0e07: tun_flow_delete.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tun_flow_delete(struct tun_struct *tun, struct tun_flow_entry *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8188b177)
Location: drivers/net/tun.c:410
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
```
**Symbols:**

```
ffffffff8188a000-ffffffff8188a061: tun_flow_delete (STB_LOCAL)
ffffffff8189090e-ffffffff8189092c: tun_flow_delete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tun_flow_delete(struct tun_struct *tun, struct tun_flow_entry *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81899317)
Location: drivers/net/tun.c:381
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
```
**Symbols:**

```
ffffffff818981a0-ffffffff81898201: tun_flow_delete (STB_LOCAL)
ffffffff81c19581-ffffffff81c1959f: tun_flow_delete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tun_flow_delete(struct tun_struct *tun, struct tun_flow_entry *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8187b6f7)
Location: drivers/net/tun.c:389
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
```
**Symbols:**

```
ffffffff8187aa70-ffffffff8187aad1: tun_flow_delete (STB_LOCAL)
ffffffff81c0b3dd-ffffffff81c0b3fb: tun_flow_delete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tun_flow_delete(struct tun_struct *tun, struct tun_flow_entry *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff8190cc18)
Location: drivers/net/tun.c:395
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
```
**Symbols:**

```
ffffffff8190bf90-ffffffff8190bff1: tun_flow_delete (STB_LOCAL)
ffffffff81d1095e-ffffffff81d1097c: tun_flow_delete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void tun_flow_delete(struct tun_struct *tun, struct tun_flow_entry *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81a611cc)
Location: drivers/net/tun.c:400
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
```
**Symbols:**

```
ffffffff81a5f800-ffffffff81a5f86f: tun_flow_delete (STB_LOCAL)
ffffffff81edb714-ffffffff81edb732: tun_flow_delete.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void tun_flow_delete(struct tun_struct *tun, struct tun_flow_entry *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81bec50d)
Location: drivers/net/tun.c:400
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
```
**Symbols:**

```
ffffffff81beac90-ffffffff81bead16: tun_flow_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void tun_flow_delete(struct tun_struct *tun, struct tun_flow_entry *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81c44b8c)
Location: drivers/net/tun.c:400
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
```
**Symbols:**

```
ffffffff81c430d0-ffffffff81c43154: tun_flow_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void tun_flow_delete(struct tun_struct *tun, struct tun_flow_entry *e);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffff81cfa6ec)
Location: drivers/net/tun.c:400
Inline: True
Inline callers:
  - drivers/net/tun.c:tun_flow_flush
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
```
**Symbols:**

```
ffffffff81cf8830-ffffffff81cf88b4: tun_flow_delete (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffff8000109db208)
Location: drivers/net/tun.c:439
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffff8000109db208-ffff8000109db268: tun_flow_delete.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tun_flow_delete(struct tun_struct *tun, struct tun_flow_entry *e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c0ac17c4)
Location: drivers/net/tun.c:439
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
c0ac17c4-c0ac1820: tun_flow_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tun_flow_delete(struct tun_struct *tun, struct tun_flow_entry *e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (c000000000a9cc20)
Location: drivers/net/tun.c:439
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
c000000000a9cc20-c000000000a9ccac: tun_flow_delete (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tun_flow_delete(struct tun_struct *tun, struct tun_flow_entry *e);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/tun.c (ffffffe000625914)
Location: drivers/net/tun.c:439
Inline: False
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffe000625914-ffffffe000625968: tun_flow_delete (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff81785890)
Location: drivers/net/tun.c:439
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff81785890-ffffffff817858d7: tun_flow_delete.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817651e0)
Location: drivers/net/tun.c:439
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff817651e0-ffffffff81765227: tun_flow_delete.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817b5c40)
Location: drivers/net/tun.c:439
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff817b5c40-ffffffff817b5c87: tun_flow_delete.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/net/tun.c (ffffffff817cffe0)
Location: drivers/net/tun.c:439
Inline: True
Direct callers:
  - drivers/net/tun.c:__tun_detach
  - drivers/net/tun.c:tun_flow_cleanup
  - drivers/net/tun.c:tun_flow_flush
```
**Symbols:**

```
ffffffff817cffe0-ffffffff817d0027: tun_flow_delete.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
