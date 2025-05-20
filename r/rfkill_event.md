# Function: <code>rfkill_event</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81811a06)
Location: net/rfkill/core.c:225
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_uevent_work
```
```
In net/rfkill/input.c (ffffffff81812780)
Location: net/rfkill/input.c:196
Inline: True
```
**Symbols:**

```
ffffffff81812780-ffffffff8181282f: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81885069)
Location: net/rfkill/core.c:227
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81885660)
Location: net/rfkill/input.c:196
Inline: True
```
**Symbols:**

```
ffffffff81885660-ffffffff8188570f: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff818b98d9)
Location: net/rfkill/core.c:227
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff818b9ed0)
Location: net/rfkill/input.c:196
Inline: True
```
**Symbols:**

```
ffffffff818b9ed0-ffffffff818b9f7f: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff818e02e9)
Location: net/rfkill/core.c:284
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff818e08e0)
Location: net/rfkill/input.c:196
Inline: True
```
**Symbols:**

```
ffffffff818e08e0-ffffffff818e098f: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81965ff9)
Location: net/rfkill/core.c:284
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff819665f0)
Location: net/rfkill/input.c:196
Inline: True
```
**Symbols:**

```
ffffffff819665f0-ffffffff819666a5: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff819bf889)
Location: net/rfkill/core.c:298
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff819bfed0)
Location: net/rfkill/input.c:196
Inline: True
```
**Symbols:**

```
ffffffff819bfed0-ffffffff819bff85: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff819f6c19)
Location: net/rfkill/core.c:300
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff819f7070)
Location: net/rfkill/input.c:196
Inline: True
```
**Symbols:**

```
ffffffff819f7070-ffffffff819f7141: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81a6610b)
Location: net/rfkill/core.c:288
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81a665b0)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff81a665b0-ffffffff81a66681: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81a9cc7b)
Location: net/rfkill/core.c:288
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81a9d0d0)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff81a9d0d0-ffffffff81a9d1a1: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81b9768b)
Location: net/rfkill/core.c:288
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81b98b90)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff81b98b90-ffffffff81b98d5a: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81ba734b)
Location: net/rfkill/core.c:290
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81ba8860)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff81ba8860-ffffffff81ba8a2a: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81b964db)
Location: net/rfkill/core.c:291
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81b97800)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff81b97800-ffffffff81b979ca: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81c62fdb)
Location: net/rfkill/core.c:291
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81c64370)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff81c64370-ffffffff81c6440a: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81e0595b)
Location: net/rfkill/core.c:291
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81e07050)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff81e07050-ffffffff81e07146: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81fdabdb)
Location: net/rfkill/core.c:291
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81fdc490)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff81fdc490-ffffffff81fdc586: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff820568cb)
Location: net/rfkill/core.c:291
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff82058170)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff82058170-ffffffff82058266: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff82128f8b)
Location: net/rfkill/core.c:292
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff8212acb0)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff8212acb0-ffffffff8212ada6: rfkill_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffff800010d6bf68)
Location: net/rfkill/core.c:288
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffff800010d6df20)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffff800010d6df20-ffff800010d6e048: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (c0e6b0b0)
Location: net/rfkill/core.c:288
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (c0e6b7b4)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
c0e6b7b4-c0e6b8b8: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (c000000000eaae4c)
Location: net/rfkill/core.c:288
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (c000000000eab820)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
c000000000eab820-c000000000eab9b4: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffe00089f390)
Location: net/rfkill/core.c:288
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffe00089f8d0)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffe00089f8d0-ffffffe00089f9c4: rfkill_event (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81a3c00b)
Location: net/rfkill/core.c:288
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81a3c460)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff81a3c460-ffffffff81a3c531: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff819f8c2b)
Location: net/rfkill/core.c:288
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff819f9080)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff819f9080-ffffffff819f9151: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81aa7ebb)
Location: net/rfkill/core.c:288
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81aa8310)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff81aa8310-ffffffff81aa83e1: rfkill_event (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision, Selective Inline ⚠️</summary>

```c
void rfkill_event(struct rfkill *rfkill);
```

**Collision:** Static-Static Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/rfkill/core.c (ffffffff81ab425b)
Location: net/rfkill/core.c:288
Inline: True
Inline callers:
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_uevent_work
  - net/rfkill/core.c:rfkill_set_block
  - net/rfkill/core.c:rfkill_set_block
```
```
In net/rfkill/input.c (ffffffff81ab4870)
Location: net/rfkill/input.c:193
Inline: True
```
**Symbols:**

```
ffffffff81ab4870-ffffffff81ab4941: rfkill_event (STB_LOCAL)
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
