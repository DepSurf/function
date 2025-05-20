# Function: <code>get_free_page_and_send</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8160b999)
Location: drivers/virtio/virtio_balloon.c:581
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:report_free_page_func
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
In drivers/virtio/virtio_balloon.c (ffffffff8163f667)
Location: drivers/virtio/virtio_balloon.c:572
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffffffff81661a87)
Location: drivers/virtio/virtio_balloon.c:576
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int get_free_page_and_send(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8170f9d0)
Location: drivers/virtio/virtio_balloon.c:629
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
**Symbols:**

```
ffffffff8170f9d0-ffffffff8170fb27: get_free_page_and_send (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int get_free_page_and_send(struct virtio_balloon *vb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/virtio/virtio_balloon.c (ffffffff8172c7d0)
Location: drivers/virtio/virtio_balloon.c:621
Inline: False
Direct callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
```
**Symbols:**

```
ffffffff8172c7d0-ffffffff8172c927: get_free_page_and_send (STB_LOCAL)
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
In drivers/virtio/virtio_balloon.c (ffffffff817119d5)
Location: drivers/virtio/virtio_balloon.c:621
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffffffff8178e445)
Location: drivers/virtio/virtio_balloon.c:621
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffffffff818c4d13)
Location: drivers/virtio/virtio_balloon.c:621
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffffffff81a15551)
Location: drivers/virtio/virtio_balloon.c:614
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffffffff81a5e611)
Location: drivers/virtio/virtio_balloon.c:614
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffffffff81ab0d01)
Location: drivers/virtio/virtio_balloon.c:653
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffff80001082a36c)
Location: drivers/virtio/virtio_balloon.c:576
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (c0947898)
Location: drivers/virtio/virtio_balloon.c:576
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (c0000000008d7164)
Location: drivers/virtio/virtio_balloon.c:576
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffffffe00052035e)
Location: drivers/virtio/virtio_balloon.c:576
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffffffff816278f7)
Location: drivers/virtio/virtio_balloon.c:576
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffffffff8161bf77)
Location: drivers/virtio/virtio_balloon.c:576
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffffffff816558c7)
Location: drivers/virtio/virtio_balloon.c:576
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
In drivers/virtio/virtio_balloon.c (ffffffff8166ef47)
Location: drivers/virtio/virtio_balloon.c:576
Inline: True
Inline callers:
  - drivers/virtio/virtio_balloon.c:virtio_balloon_report_free_page
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
