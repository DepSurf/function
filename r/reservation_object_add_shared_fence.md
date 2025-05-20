# Function: <code>reservation_object_add_shared_fence</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void reservation_object_add_shared_fence(struct reservation_object *obj, struct fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff815a5410)
Location: drivers/dma-buf/reservation.c:187
Inline: True
```
**Symbols:**

```
ffffffff815a5410-ffffffff815a5633: reservation_object_add_shared_fence (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void reservation_object_add_shared_fence(struct reservation_object *obj, struct fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff815fc550)
Location: drivers/dma-buf/reservation.c:210
Inline: True
```
**Symbols:**

```
ffffffff815fc550-ffffffff815fc7af: reservation_object_add_shared_fence (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void reservation_object_add_shared_fence(struct reservation_object *obj, struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff8162a8e0)
Location: drivers/dma-buf/reservation.c:210
Inline: True
```
**Symbols:**

```
ffffffff8162a8e0-ffffffff8162ab3f: reservation_object_add_shared_fence (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void reservation_object_add_shared_fence(struct reservation_object *obj, struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81640810)
Location: drivers/dma-buf/reservation.c:210
Inline: True
```
**Symbols:**

```
ffffffff81640810-ffffffff816409c0: reservation_object_add_shared_fence (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void reservation_object_add_shared_fence(struct reservation_object *obj, struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff816a95d0)
Location: drivers/dma-buf/reservation.c:209
Inline: True
```
**Symbols:**

```
ffffffff816a95d0-ffffffff816a978f: reservation_object_add_shared_fence (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void reservation_object_add_shared_fence(struct reservation_object *obj, struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff816e59a0)
Location: drivers/dma-buf/reservation.c:226
Inline: False
```
**Symbols:**

```
ffffffff816e59a0-ffffffff816e5c9b: reservation_object_add_shared_fence (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void reservation_object_add_shared_fence(struct reservation_object *obj, struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81708ef0)
Location: drivers/dma-buf/reservation.c:146
Inline: False
```
**Symbols:**

```
ffffffff81708ef0-ffffffff81709030: reservation_object_add_shared_fence (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void reservation_object_add_shared_fence(struct reservation_object *obj, struct dma_fence *fence);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81744490)
Location: drivers/dma-buf/reservation.c:148
Inline: False
```
**Symbols:**

```
ffffffff81744490-ffffffff817445a1: reservation_object_add_shared_fence (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct fence *fence</code> ➡️ <code>struct dma_fence *fence</code>
</li>
</ul>
</details>
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
