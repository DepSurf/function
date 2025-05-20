# Function: <code>reservation_object_reserve_shared</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int reservation_object_reserve_shared(struct reservation_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff815a4f40)
Location: drivers/dma-buf/reservation.c:50
Inline: True
```
**Symbols:**

```
ffffffff815a4f40-ffffffff815a4fbb: reservation_object_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int reservation_object_reserve_shared(struct reservation_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff815fbfd0)
Location: drivers/dma-buf/reservation.c:69
Inline: True
```
**Symbols:**

```
ffffffff815fbfd0-ffffffff815fc04d: reservation_object_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int reservation_object_reserve_shared(struct reservation_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff8162a5d0)
Location: drivers/dma-buf/reservation.c:69
Inline: True
```
**Symbols:**

```
ffffffff8162a5d0-ffffffff8162a64d: reservation_object_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int reservation_object_reserve_shared(struct reservation_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff816400c0)
Location: drivers/dma-buf/reservation.c:69
Inline: True
```
**Symbols:**

```
ffffffff816400c0-ffffffff8164013b: reservation_object_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int reservation_object_reserve_shared(struct reservation_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff816a89b0)
Location: drivers/dma-buf/reservation.c:69
Inline: True
```
**Symbols:**

```
ffffffff816a89b0-ffffffff816a8a2b: reservation_object_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int reservation_object_reserve_shared(struct reservation_object *obj);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff816e4c90)
Location: drivers/dma-buf/reservation.c:69
Inline: True
```
**Symbols:**

```
ffffffff816e4c90-ffffffff816e4d08: reservation_object_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int reservation_object_reserve_shared(struct reservation_object *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff817089a0)
Location: drivers/dma-buf/reservation.c:70
Inline: False
```
**Symbols:**

```
ffffffff817089a0-ffffffff81708b9a: reservation_object_reserve_shared (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int reservation_object_reserve_shared(struct reservation_object *obj, unsigned int num_fences);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81743a40)
Location: drivers/dma-buf/reservation.c:70
Inline: False
```
**Symbols:**

```
ffffffff81743a40-ffffffff81743c07: reservation_object_reserve_shared (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int num_fences</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
