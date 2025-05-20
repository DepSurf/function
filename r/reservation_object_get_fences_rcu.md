# Function: <code>reservation_object_get_fences_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int reservation_object_get_fences_rcu(struct reservation_object *obj, struct fence **pfence_excl, unsigned int *pshared_count, struct fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff815a4fc0)
Location: drivers/dma-buf/reservation.c:236
Inline: False
```
**Symbols:**

```
ffffffff815a4fc0-ffffffff815a51dd: reservation_object_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int reservation_object_get_fences_rcu(struct reservation_object *obj, struct fence **pfence_excl, unsigned int *pshared_count, struct fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff815fc2e0)
Location: drivers/dma-buf/reservation.c:278
Inline: False
```
**Symbols:**

```
ffffffff815fc2e0-ffffffff815fc544: reservation_object_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int reservation_object_get_fences_rcu(struct reservation_object *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff8162a650)
Location: drivers/dma-buf/reservation.c:278
Inline: False
```
**Symbols:**

```
ffffffff8162a650-ffffffff8162a8d8: reservation_object_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int reservation_object_get_fences_rcu(struct reservation_object *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81640140)
Location: drivers/dma-buf/reservation.c:278
Inline: False
```
**Symbols:**

```
ffffffff81640140-ffffffff816402d6: reservation_object_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int reservation_object_get_fences_rcu(struct reservation_object *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff816a8a30)
Location: drivers/dma-buf/reservation.c:364
Inline: False
```
**Symbols:**

```
ffffffff816a8a30-ffffffff816a8c88: reservation_object_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int reservation_object_get_fences_rcu(struct reservation_object *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff816e4db0)
Location: drivers/dma-buf/reservation.c:381
Inline: False
```
**Symbols:**

```
ffffffff816e4db0-ffffffff816e5117: reservation_object_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int reservation_object_get_fences_rcu(struct reservation_object *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81708080)
Location: drivers/dma-buf/reservation.c:322
Inline: False
```
**Symbols:**

```
ffffffff81708080-ffffffff817083cb: reservation_object_get_fences_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int reservation_object_get_fences_rcu(struct reservation_object *obj, struct dma_fence **pfence_excl, unsigned int *pshared_count, struct dma_fence ***pshared);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81743c10)
Location: drivers/dma-buf/reservation.c:330
Inline: False
```
**Symbols:**

```
ffffffff81743c10-ffffffff81743f0b: reservation_object_get_fences_rcu (STB_GLOBAL)
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
<code>struct fence **pfence_excl</code> ➡️ <code>struct dma_fence **pfence_excl</code>
</li>
<li>
<b>Param type changed. </b>
<code>struct fence ***pshared</code> ➡️ <code>struct dma_fence ***pshared</code>
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
