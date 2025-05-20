# Function: <code>deadline_merged_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void deadline_merged_request(struct request_queue *q, struct request *req, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff813dc8f0)
Location: block/deadline-iosched.c:154
Inline: False
```
**Symbols:**

```
ffffffff813dc8f0-ffffffff813dc935: deadline_merged_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void deadline_merged_request(struct request_queue *q, struct request *req, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff81422500)
Location: block/deadline-iosched.c:153
Inline: False
```
**Symbols:**

```
ffffffff81422500-ffffffff81422557: deadline_merged_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void deadline_merged_request(struct request_queue *q, struct request *req, int type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff8143d650)
Location: block/deadline-iosched.c:153
Inline: False
```
**Symbols:**

```
ffffffff8143d650-ffffffff8143d693: deadline_merged_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void deadline_merged_request(struct request_queue *q, struct request *req, enum elv_merge type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff8144ca80)
Location: block/deadline-iosched.c:149
Inline: False
```
**Symbols:**

```
ffffffff8144ca80-ffffffff8144cac4: deadline_merged_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void deadline_merged_request(struct request_queue *q, struct request *req, enum elv_merge type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff81479180)
Location: block/deadline-iosched.c:149
Inline: False
```
**Symbols:**

```
ffffffff81479180-ffffffff814791c4: deadline_merged_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void deadline_merged_request(struct request_queue *q, struct request *req, enum elv_merge type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/deadline-iosched.c (ffffffff814ad910)
Location: block/deadline-iosched.c:153
Inline: False
```
**Symbols:**

```
ffffffff814ad910-ffffffff814ad953: deadline_merged_request (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int type</code> ➡️ <code>enum elv_merge type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
</ul>
