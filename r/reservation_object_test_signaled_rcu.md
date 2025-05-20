# Function: <code>reservation_object_test_signaled_rcu</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
bool reservation_object_test_signaled_rcu(struct reservation_object *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff815a51e0)
Location: drivers/dma-buf/reservation.c:419
Inline: False
Direct callers:
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
**Symbols:**

```
ffffffff815a51e0-ffffffff815a5404: reservation_object_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool reservation_object_test_signaled_rcu(struct reservation_object *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff815fc050)
Location: drivers/dma-buf/reservation.c:483
Inline: False
Direct callers:
  - drivers/dma-buf/reservation.c:reservation_object_wait_timeout_rcu
```
**Symbols:**

```
ffffffff815fc050-ffffffff815fc2dc: reservation_object_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool reservation_object_test_signaled_rcu(struct reservation_object *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff8162ac70)
Location: drivers/dma-buf/reservation.c:472
Inline: False
```
**Symbols:**

```
ffffffff8162ac70-ffffffff8162aefe: reservation_object_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool reservation_object_test_signaled_rcu(struct reservation_object *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81640370)
Location: drivers/dma-buf/reservation.c:472
Inline: False
```
**Symbols:**

```
ffffffff81640370-ffffffff8164053d: reservation_object_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool reservation_object_test_signaled_rcu(struct reservation_object *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff816a9360)
Location: drivers/dma-buf/reservation.c:557
Inline: False
```
**Symbols:**

```
ffffffff816a9360-ffffffff816a95cd: reservation_object_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool reservation_object_test_signaled_rcu(struct reservation_object *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff816e53e0)
Location: drivers/dma-buf/reservation.c:586
Inline: False
```
**Symbols:**

```
ffffffff816e53e0-ffffffff816e5656: reservation_object_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool reservation_object_test_signaled_rcu(struct reservation_object *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff817083d0)
Location: drivers/dma-buf/reservation.c:527
Inline: False
```
**Symbols:**

```
ffffffff817083d0-ffffffff8170865e: reservation_object_test_signaled_rcu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool reservation_object_test_signaled_rcu(struct reservation_object *obj, bool test_all);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dma-buf/reservation.c (ffffffff81743f10)
Location: drivers/dma-buf/reservation.c:539
Inline: False
```
**Symbols:**

```
ffffffff81743f10-ffffffff81744117: reservation_object_test_signaled_rcu (STB_GLOBAL)
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
