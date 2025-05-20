# Function: <code>input_mt_set_slots</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8166a5f2)
Location: drivers/input/input-mt.c:367
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff816ca89f)
Location: drivers/input/input-mt.c:382
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff816f885f)
Location: drivers/input/input-mt.c:382
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8170e390)
Location: drivers/input/input-mt.c:382
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8177f5c0)
Location: drivers/input/input-mt.c:382
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff817c06af)
Location: drivers/input/input-mt.c:386
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff817e7b9f)
Location: drivers/input/input-mt.c:386
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff818286e8)
Location: drivers/input/input-mt.c:383
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff81859c58)
Location: drivers/input/input-mt.c:383
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void input_mt_set_slots(struct input_mt *mt, int *slots, int num_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8192c690)
Location: drivers/input/input-mt.c:383
Inline: False
Direct callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
**Symbols:**

```
ffffffff8192c690-ffffffff8192c78a: input_mt_set_slots (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void input_mt_set_slots(struct input_mt *mt, int *slots, int num_pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff81933b80)
Location: drivers/input/input-mt.c:386
Inline: False
Direct callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
**Symbols:**

```
ffffffff81933b80-ffffffff81933c7a: input_mt_set_slots (STB_LOCAL)
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
In drivers/input/input-mt.c (ffffffff8191709d)
Location: drivers/input/input-mt.c:386
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
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
In drivers/input/input-mt.c (ffffffff819b930d)
Location: drivers/input/input-mt.c:386
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
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
In drivers/input/input-mt.c (ffffffff81b18e5f)
Location: drivers/input/input-mt.c:386
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
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
In drivers/input/input-mt.c (ffffffff81caa78f)
Location: drivers/input/input-mt.c:426
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
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
In drivers/input/input-mt.c (ffffffff81d11d60)
Location: drivers/input/input-mt.c:426
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
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
In drivers/input/input-mt.c (ffffffff81dc7960)
Location: drivers/input/input-mt.c:426
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffff800010a99be4)
Location: drivers/input/input-mt.c:383
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (c0b7b8dc)
Location: drivers/input/input-mt.c:383
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (c000000000b79a54)
Location: drivers/input/input-mt.c:383
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffe0006aa626)
Location: drivers/input/input-mt.c:383
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8180ec68)
Location: drivers/input/input-mt.c:383
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff817d63b8)
Location: drivers/input/input-mt.c:383
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff8184dde8)
Location: drivers/input/input-mt.c:383
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/input/input-mt.c (ffffffff81868fb8)
Location: drivers/input/input-mt.c:383
Inline: True
Inline callers:
  - drivers/input/input-mt.c:input_mt_assign_slots
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
</ul>
