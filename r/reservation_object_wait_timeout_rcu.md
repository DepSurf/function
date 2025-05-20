# Function: <code>reservation_object_wait_timeout_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int reservation_object_wait_timeout_rcu(struct reservation_object *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff815a5720)
Location: drivers/dma-buf/reservation.c:322
Inline: False
```
**Symbols:**

```
ffffffff815a5720-ffffffff815a599a: reservation_object_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int reservation_object_wait_timeout_rcu(struct reservation_object *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff815fc8e0)
Location: drivers/dma-buf/reservation.c:376
Inline: False
```
**Symbols:**

```
ffffffff815fc8e0-ffffffff815fcbca: reservation_object_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int reservation_object_wait_timeout_rcu(struct reservation_object *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff8162af00)
Location: drivers/dma-buf/reservation.c:367
Inline: False
```
**Symbols:**

```
ffffffff8162af00-ffffffff8162b231: reservation_object_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int reservation_object_wait_timeout_rcu(struct reservation_object *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81640540)
Location: drivers/dma-buf/reservation.c:367
Inline: False
```
**Symbols:**

```
ffffffff81640540-ffffffff81640810: reservation_object_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int reservation_object_wait_timeout_rcu(struct reservation_object *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff816a8ff0)
Location: drivers/dma-buf/reservation.c:453
Inline: False
```
**Symbols:**

```
ffffffff816a8ff0-ffffffff816a9355: reservation_object_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int reservation_object_wait_timeout_rcu(struct reservation_object *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff816e5660)
Location: drivers/dma-buf/reservation.c:482
Inline: False
```
**Symbols:**

```
ffffffff816e5660-ffffffff816e5997: reservation_object_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int reservation_object_wait_timeout_rcu(struct reservation_object *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81708660)
Location: drivers/dma-buf/reservation.c:423
Inline: False
```
**Symbols:**

```
ffffffff81708660-ffffffff81708997: reservation_object_wait_timeout_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int reservation_object_wait_timeout_rcu(struct reservation_object *obj, bool wait_all, bool intr, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81744120)
Location: drivers/dma-buf/reservation.c:435
Inline: False
```
**Symbols:**

```
ffffffff81744120-ffffffff817443db: reservation_object_wait_timeout_rcu (STB_GLOBAL)
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
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
