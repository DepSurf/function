# Function: <code>crypto_shash_descsize</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/ext4/bitmap.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/jbd2/revoke.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8139b293)
Location: include/crypto/hash.h:739
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff813a351d)
Location: include/crypto/hash.h:739
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/crypto/hash.h:739
Inline: True
```
```
In lib/digsig.c (ffffffff814197a6)
Location: include/crypto/hash.h:739
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/bitmap.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff813392d2)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ecryptfs/keystore.c (ffffffff8133d275)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/trusted.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813d80eb)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff813df69d)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff813f19e3)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff813f2882)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In lib/digsig.c (ffffffff81461514)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/bitmap.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff8134f072)
Location: include/crypto/hash.h:777
Inline: True
```
```
In fs/ecryptfs/keystore.c (ffffffff81353005)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/trusted.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813efd9b)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff813f7c2d)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8140b233)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8140c0f2)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/crypto/hash.h:777
Inline: True
```
```
In lib/digsig.c (ffffffff81480034)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff8202b23a)
Location: include/crypto/hash.h:777
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/crypto/keyinfo.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/ext4/bitmap.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81363b22)
Location: include/crypto/hash.h:783
Inline: True
```
```
In fs/ecryptfs/keystore.c (ffffffff81367c7a)
Location: include/crypto/hash.h:783
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81398d2c)
Location: include/crypto/hash.h:783
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (ffffffff813fc3c3)
Location: include/crypto/hash.h:783
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8140411d)
Location: include/crypto/hash.h:783
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81418dd3)
Location: include/crypto/hash.h:783
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81419cfd)
Location: include/crypto/hash.h:783
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/crypto/hash.h:783
Inline: True
```
```
In lib/digsig.c (ffffffff814892d1)
Location: include/crypto/hash.h:783
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff8210e905)
Location: include/crypto/hash.h:783
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/crypto/keyinfo.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/ext4/bitmap.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/ext4/extents.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/ext4/ialloc.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/ext4/inode.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/ext4/mmp.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/ext4/namei.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/ext4/super.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/ext4/xattr.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/jbd2/commit.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/jbd2/recovery.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/jbd2/journal.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffffffff81388892)
Location: include/crypto/hash.h:791
Inline: True
```
```
In fs/ecryptfs/keystore.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In security/keys/dh.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In security/keys/trusted.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813be53c)
Location: include/crypto/hash.h:791
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/apparmor/crypto.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In security/integrity/ima/ima_crypto.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8142489b)
Location: include/crypto/hash.h:791
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8142c9dd)
Location: include/crypto/hash.h:791
Inline: True
Inline callers:
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In crypto/drbg.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81443903)
Location: include/crypto/hash.h:791
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81444830)
Location: include/crypto/hash.h:791
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (0)
Location: include/crypto/hash.h:791
Inline: True
```
```
In lib/digsig.c (ffffffff814c5411)
Location: include/crypto/hash.h:791
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff82718cbe)
Location: include/crypto/hash.h:791
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811396e3)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/keyinfo.c (ffffffff812fbe7f)
Location: include/crypto/hash.h:790
Inline: True
```
```
In fs/ext4/bitmap.c (ffffffff8133718d)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff813397d1)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81348429)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813545f4)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/ext4/inode.c:ext4_iget
  - fs/ext4/inode.c:ext4_iget
```
```
In fs/ext4/mmp.c (ffffffff81367159)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81369252)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
```
```
In fs/ext4/super.c (ffffffff81386975)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff8138de02)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/jbd2/commit.c (ffffffff81395f7e)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81397a95)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff8139c46e)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/crypto.c (ffffffff813b76b0)
Location: include/crypto/hash.h:790
Inline: True
```
```
In fs/ecryptfs/keystore.c (ffffffff813bb2e1)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff813ec371)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff813ed385)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff813ef40c)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/apparmor/crypto.c (ffffffff8144e7ef)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - security/apparmor/crypto.c:aa_calc_profile_hash
  - security/apparmor/crypto.c:aa_calc_hash
```
```
In security/integrity/ima/ima_crypto.c (ffffffff81452e51)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - security/integrity/ima/ima_crypto.c:ima_calc_buffer_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_file_hash
  - security/integrity/ima/ima_crypto.c:ima_calc_boot_aggregate
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81456fd7)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81460103)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814637a7)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
  - crypto/hmac.c:hmac_setkey
```
```
In crypto/drbg.c (ffffffff814731f6)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8147683b)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81477757)
Location: include/crypto/hash.h:790
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81478346)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffff814f630f)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff8274343c)
Location: include/crypto/hash.h:790
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81144fb3)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/ext4/bitmap.c (ffffffff8134e40d)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff81350971)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff813605d9)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8136c91c)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff81373af1)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff8137f5d9)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813816f2)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirent_node
```
```
In fs/ext4/super.c (ffffffff8139f475)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_load_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813a6382)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/jbd2/commit.c (ffffffff813aecd4)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813b081b)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813b522e)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/crypto.c (ffffffff813d0906)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In fs/ecryptfs/keystore.c (ffffffff813d48f0)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff81406f67)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81408565)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8140a6a1)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81474486)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8147db72)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff81481427)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff81490f76)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814949db)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81495962)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_verify
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8149656d)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffff8150a70f)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In arch/x86/power/hibernate.c (ffffffff8188f0ba)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff828fd732)
Location: include/crypto/hash.h:802
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811503ac)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/ext4/bitmap.c (ffffffff81376dcd)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff813795e6)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81389759)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81395ef1)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8139d11d)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813a8a58)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813aa991)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813c91c3)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813d0c1f)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/jbd2/commit.c (ffffffff813d91cf)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dadae)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813df8a4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/crypto.c (ffffffff813fb51e)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In fs/ecryptfs/keystore.c (ffffffff813ff298)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff814340e0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81435d15)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff814378b9)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a21be)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814abe00)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814af60e)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff814be106)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814c23c4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814c36f8)
Location: include/crypto/hash.h:801
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c400c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81539232)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In arch/x86/power/hibernate.c (ffffffff818d90b9)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff8291a2c5)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115c03c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff8134ba35)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ext4/bitmap.c (ffffffff8138f03d)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8139185f)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/ialloc.c (ffffffff813a2089)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813ae8e1)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813b5b8d)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813c1968)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813c38c1)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813e2571)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813ea2ef)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/jbd2/commit.c (ffffffff813f31d1)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813f4dfe)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813f9964)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/crypto.c (ffffffff814153eb)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In fs/ecryptfs/keystore.c (ffffffff81419188)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff8144de30)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff8144fab5)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81451a86)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814bce8e)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814c6ae0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814ca299)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff814d6f56)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814db1f4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814dc557)
Location: include/crypto/hash.h:801
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814dceec)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8155a052)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In arch/x86/power/hibernate.c (ffffffff8190b0b9)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff82924134)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116cf9c)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81391385)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/ext4/bitmap.c (ffffffff813da5cd)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff813dd616)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff813ee183)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813fa937)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff8140156b)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff8140db59)
Location: include/crypto/hash.h:814
Inline: True
```
```
In fs/ext4/namei.c (ffffffff8140ff0f)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff8142e62a)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff814375c2)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/jbd2/commit.c (ffffffff8143fd2a)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/recovery.c (ffffffff81441a4b)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:scan_revoke_records
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81447249)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/keystore.c (ffffffff81468338)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff8149fc3a)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814a0d55)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_sdesc
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8151d7aa)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81525d90)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/hmac.c (ffffffff81529769)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff815364d8)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8153aae4)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8153be63)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8153ccbc)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815e3982)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81b8186f)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
```
In arch/x86/power/hibernate.c (ffffffff81bbc0d9)
Location: include/crypto/hash.h:814
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116961c)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813a27e5)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/ext4/bitmap.c (ffffffff813ec2a1)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff813eef06)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff814007c7)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8140cfaf)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff81413f5b)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff81420fc9)
Location: include/crypto/hash.h:822
Inline: True
```
```
In fs/ext4/namei.c (ffffffff814233df)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff814449d4)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/xattr.c (ffffffff814500f2)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff814549a4)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/jbd2/commit.c (ffffffff8145bdfa)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
  - fs/jbd2/commit.c:jbd2_block_tag_csum_set
```
```
In fs/jbd2/recovery.c (ffffffff8145e62d)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814637a9)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/keystore.c (ffffffff814837b8)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff814bd64a)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814be705)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_sdesc
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8153a61d)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81542cc5)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/hmac.c (ffffffff81546719)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff81553448)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81557915)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81558b03)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8155981c)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81607e12)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c330ec)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
```
In arch/x86/power/hibernate.c (ffffffff81bd10b9)
Location: include/crypto/hash.h:822
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116a34e)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813a9968)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/ext4/bitmap.c (ffffffff813f27e4)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff813f53a4)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff81406c77)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8141312b)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff8141a1cb)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff81427779)
Location: include/crypto/hash.h:826
Inline: True
```
```
In fs/ext4/namei.c (ffffffff81429be2)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff8144a25e)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_update_super
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
```
```
In fs/ext4/xattr.c (ffffffff814558e7)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff8145a0d8)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/jbd2/commit.c (ffffffff81462450)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff81463eba)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814688f7)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/keystore.c (ffffffff81489244)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff814c34ba)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff814c49c5)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_sdesc
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81542cdd)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8154b365)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/hmac.c (ffffffff8154edd9)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff8155bbc8)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff81560215)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81561433)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8156212c)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815eab22)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81c253f3)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8118ff0e)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff813f91a8)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/ext4/bitmap.c (ffffffff814447c4)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff81447ae3)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff814594fb)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81466486)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff8146d3bb)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff8147b509)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8147d972)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff814a0ba4)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff814a9907)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff814adf58)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/ext4/orphan.c (ffffffff814b21ac)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
```
```
In fs/jbd2/commit.c (ffffffff814b7946)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814b948f)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff814be3a7)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/keystore.c (ffffffff814e0a44)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff8151beaa)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/keys/dh.c:kdf_alloc
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8151d3a5)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_sdesc
```
```
In security/integrity/evm/evm_crypto.c (ffffffff815a33e8)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff815abb45)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/hmac.c (ffffffff815af729)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff815bcef8)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff815c15c5)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff815c2893)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff815c353c)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81657022)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81d41780)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811bf6cc)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff8146c022)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/ext4/bitmap.c (ffffffff814c0734)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff814c4016)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff814d6ef2)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff814e5fb2)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff814edc40)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff814fd98f)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff81500676)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff81527687)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:__ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff81531c57)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff81536494)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_memcpy
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/ext4/orphan.c (ffffffff8153ad9f)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
```
```
In fs/jbd2/commit.c (ffffffff815410f9)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8154300f)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81549e53)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/keystore.c (ffffffff8156ebdc)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff815b0715)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_sdesc
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81649c46)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81653475)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/hmac.c (ffffffff81657eab)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff81666896)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8166ba3e)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff8166cdc2)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff8166db1c)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff8166e189)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff8176e860)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81f0e0e5)
Location: include/crypto/hash.h:826
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff812019ec)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff814fd352)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/ext4/bitmap.c (ffffffff815587d4)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8155c632)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff8156fc77)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff8157f731)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff81587af0)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff8159816f)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff8159b156)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff815c5767)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff815d01f2)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff815d4f38)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/ext4/orphan.c (ffffffff815d935f)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
```
```
In fs/jbd2/commit.c (ffffffff815dfc40)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff815e1def)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff815ea6ed)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/keystore.c (ffffffff81613d2d)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff8165b105)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_sdesc
```
```
In security/integrity/evm/evm_crypto.c (ffffffff81702c86)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff8170d1b5)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/hmac.c (ffffffff81712173)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff81720c92)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff8172665e)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81727dc2)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81728c0c)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff81729379)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff8189e150)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffff81fbe4df)
Location: include/crypto/hash.h:828
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81216dbc)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff815348b5)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/ext4/bitmap.c (ffffffff81590624)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff81594432)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff815a7af9)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff815b6be2)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff815be370)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff815cec1f)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff815d19d6)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff815fd389)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff81607a12)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff8160cb08)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/ext4/orphan.c (ffffffff81610edb)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
```
```
In fs/jbd2/commit.c (ffffffff81617939)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff81619873)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81620d8a)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/keystore.c (ffffffff8164bd8d)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816939f5)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_sdesc
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8173cc16)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff81746b76)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/hmac.c (ffffffff8174ce43)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff8175c542)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/jitterentropy-kcapi.c (ffffffff836fd3f4)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
  - crypto/jitterentropy-kcapi.c:jent_hash_time
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff817629dc)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff81764212)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff81764f3c)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff817656d9)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff818e0710)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/base/firmware_loader/main.c (ffffffff81b5e65f)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
```
```
In net/ipv6/seg6_hmac.c (ffffffff8201f33f)
Location: include/crypto/hash.h:880
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8122ec9c)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81569875)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
```
```
In fs/ext4/bitmap.c (ffffffff815c9364)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff815cd122)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffff815e0910)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff815ef982)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffff815f7130)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
  - fs/ext4/ioctl.c:ext4_reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff8160749f)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block_thawed
```
```
In fs/ext4/namei.c (ffffffff8160a176)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
  - fs/ext4/namei.c:ext4_dirblock_csum_verify
```
```
In fs/ext4/super.c (ffffffff81635eef)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_journal_blkdev
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_init_metadata_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff81640752)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/ext4/fast_commit.c (ffffffff816458c8)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ext4/fast_commit.c:ext4_fc_write_tail
  - fs/ext4/fast_commit.c:ext4_fc_reserve_space
```
```
In fs/ext4/orphan.c (ffffffff81649c9b)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_init_orphan_info
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
  - fs/ext4/orphan.c:ext4_orphan_file_block_trigger
```
```
In fs/jbd2/commit.c (ffffffff816507d4)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:journal_submit_commit_record
```
```
In fs/jbd2/recovery.c (ffffffff8165277f)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff816599ca)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/jbd2/journal.c:jbd2_journal_set_features
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:journal_load_superblock
  - fs/jbd2/journal.c:journal_check_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/keystore.c (ffffffff816852bc)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/trusted-keys/trusted_tpm1.c (ffffffff816cfff5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - security/keys/trusted-keys/trusted_tpm1.c:init_sdesc
```
```
In security/integrity/evm/evm_crypto.c (ffffffff8177dab6)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/ahash.c (ffffffff817876cd)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/ahash.c:crypto_ahash_init_tfm
```
```
In crypto/shash.c (ffffffff81788230)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/shash.c:crypto_shash_import
  - crypto/shash.c:crypto_shash_export
  - crypto/shash.c:crypto_shash_tfm_digest
```
```
In crypto/hmac.c (ffffffff8178e5e5)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff8179e442)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/jitterentropy-kcapi.c (ffffffff83930a04)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/jitterentropy-kcapi.c:jent_mod_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_init
  - crypto/jitterentropy-kcapi.c:jent_kcapi_cleanup
  - crypto/jitterentropy-kcapi.c:jent_hash_time
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff817a44cc)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff817a5e32)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff817a6b5c)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In crypto/kdf_sp800108.c (ffffffff817a72d9)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - crypto/kdf_sp800108.c:crypto_kdf108_ctr_generate
```
```
In lib/digsig.c (ffffffff81927250)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In drivers/base/firmware_loader/main.c (ffffffff81bb1fcd)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - drivers/base/firmware_loader/main.c:fw_log_firmware_info
```
```
In net/ipv6/seg6_hmac.c (ffffffff820ee46f)
Location: include/crypto/hash.h:806
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init_algo
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffff80001040c490)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ext4/bitmap.c (ffff800010461504)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/extents.c (ffff80001046440c)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/ialloc.c (ffff800010473d04)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/inode.c (ffff80001047da14)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/ioctl.c (ffff80001048a3dc)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/mmp.c (ffff800010498dfc)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/namei.c (ffff80001049b10c)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/super.c (ffff8000104ad4bc)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/xattr.c (ffff8000104c210c)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/jbd2/commit.c (ffff8000104cd894)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/jbd2/recovery.c (ffff8000104cfdec)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/jbd2/journal.c (ffff8000104d3c4c)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ecryptfs/crypto.c (ffff8000104f6a6c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In fs/ecryptfs/keystore.c (ffff8000104fa99c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffff8000105386b4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffff80001053a458)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (ffff80001053d00c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/integrity/evm/evm_crypto.c (ffff8000105b5b88)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffff8000105c1fd0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffff8000105c5fa4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffff8000105d1f6c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffff8000105d74a4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffff8000105d8b50)
Location: include/crypto/hash.h:801
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffff8000105d944c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffff800010666838)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffff8000114b519c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (c05d95bc)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ext4/bitmap.c (c06219d0)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/extents.c (c0624674)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_chksum
```
```
In fs/ext4/ialloc.c (c0635308)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/inode.c (c063f68c)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/ioctl.c (c064c398)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/mmp.c (c065a8c0)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/namei.c (c065cc38)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/super.c (c067626c)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ext4/xattr.c (c0686214)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/jbd2/commit.c (c0690858)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/jbd2/recovery.c (c06928d8)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/jbd2/journal.c (c0697084)
Location: include/crypto/hash.h:801
Inline: True
```
```
In fs/ecryptfs/crypto.c (c06b44cc)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In fs/ecryptfs/keystore.c (c06b811c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (c06ef08c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (c06f0d84)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (c06f2c8c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/integrity/evm/evm_crypto.c (c0764c88)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (c076f54c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (c0772c8c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (c0780378)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (c0784b54)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (c07860a4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/pkcs7_verify.c:pkcs7_digest
```
```
In crypto/asymmetric_keys/verify_pefile.c (c0786c7c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (c080f49c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (c15ba458)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (c000000000234be4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - kernel/kexec_file.c:__se_sys_kexec_file_load
```
```
In fs/crypto/hkdf.c (c000000000519498)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ext4/bitmap.c (c00000000057de9c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (c000000000581738)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (c000000000597330)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (c0000000005a826c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (c0000000005b1890)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (c0000000005c32bc)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (c0000000005c5d7c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (c0000000005f19ac)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (c0000000005fa7c8)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/jbd2/commit.c (c000000000607368)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (c000000000609910)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (c000000000610af4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/crypto.c (c000000000637a60)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In fs/ecryptfs/keystore.c (c00000000063d238)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (c0000000006871c0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (c000000000689cc0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (c00000000068c680)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/integrity/evm/evm_crypto.c (c0000000007396a0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (c00000000074a634)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (c00000000074f9f8)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (c00000000075fb48)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (c0000000007665ec)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (c0000000007683e0)
Location: include/crypto/hash.h:801
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (c000000000769484)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (c00000000081c3e8)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (c0000000013c7138)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/crypto/hkdf.c (ffffffe0002b5d74)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ext4/bitmap.c (ffffffe0002f0802)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffe0002f28de)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/extents.c:__ext4_ext_check
```
```
In fs/ext4/ialloc.c (ffffffe0003011d0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffe00030bada)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
  - fs/ext4/inode.c:ext4_inode_csum
```
```
In fs/ext4/ioctl.c (ffffffe00031196c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffe00031cc92)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffe00031e7f0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffe000337d70)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffe00033e0d6)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
  - fs/ext4/xattr.c:ext4_xattr_block_csum
```
```
In fs/jbd2/commit.c (ffffffe00034640c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffe000347d1c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffe00034c4cc)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
  - fs/jbd2/journal.c:jbd2_superblock_csum
```
```
In fs/ecryptfs/crypto.c (ffffffe0003656c4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In fs/ecryptfs/keystore.c (ffffffe000369158)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffe00039739e)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffe000398686)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffe00039a276)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/integrity/evm/evm_crypto.c (ffffffe0003fc9da)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffe000406b08)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffe00040a032)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffe000416c9a)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffe00041b384)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffe00041c730)
Location: include/crypto/hash.h:801
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffe00041cf7c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:verify_pefile_signature
```
```
In lib/digsig.c (ffffffe00049293e)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In net/ipv6/seg6_hmac.c (ffffffe000043fbe)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115465c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81344015)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ext4/bitmap.c (ffffffff8138761d)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff81389e3f)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/ialloc.c (ffffffff8139a669)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813a6ec1)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813ae16d)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813b9f48)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813bbea1)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813dab51)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813e28cf)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/jbd2/commit.c (ffffffff813eb7b1)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ed3de)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813f1f44)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/crypto.c (ffffffff8140d9cb)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In fs/ecryptfs/keystore.c (ffffffff81411768)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff81446410)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81448095)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8144a066)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b546e)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814bf0c0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814c2879)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff814cf536)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814d37d4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814d4b37)
Location: include/crypto/hash.h:801
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d54cc)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81552632)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In arch/x86/power/hibernate.c (ffffffff818ab0b9)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff82908e38)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8114797c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81334cf5)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ext4/bitmap.c (ffffffff813780ad)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8137a8cf)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/ialloc.c (ffffffff8138b0f9)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff81397951)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff8139ebfd)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813aa9d8)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813ac931)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813cb5d1)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813d334f)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/jbd2/commit.c (ffffffff813dc231)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813dde5e)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813e29c4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/crypto.c (ffffffff813fe44b)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In fs/ecryptfs/keystore.c (ffffffff814021e8)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff81436e60)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81438ae5)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8143aab6)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814a5e8e)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814afae0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814b3299)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff814bff56)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814c41f4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814c5557)
Location: include/crypto/hash.h:801
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814c5eec)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff81542912)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In arch/x86/power/hibernate.c (ffffffff818650b9)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff82901186)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115243c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81341ae5)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ext4/bitmap.c (ffffffff813850ed)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8138779f)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/ialloc.c (ffffffff81397ec9)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813a4721)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813ab9cd)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813b77a8)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813b9881)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813d7ff1)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813dfc4f)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/jbd2/commit.c (ffffffff813e8b31)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff813ea75e)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff813ef2c4)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/crypto.c (ffffffff8140ad4b)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In fs/ecryptfs/keystore.c (ffffffff8140eae8)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff814424b0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff81444135)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff81446106)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814b14fe)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814bb150)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814be909)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff814cb5c6)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814cf864)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814d0bc7)
Location: include/crypto/hash.h:801
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814d155c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff8154e372)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In arch/x86/power/hibernate.c (ffffffff818fc0b9)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff8291e732)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115f32c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_calculate_store_digests
```
```
In fs/crypto/hkdf.c (ffffffff81354de5)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/crypto/hkdf.c:fscrypt_hkdf_expand
  - fs/crypto/hkdf.c:hkdf_extract
```
```
In fs/ext4/bitmap.c (ffffffff81398c6d)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_block_bitmap_csum_verify
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_set
  - fs/ext4/bitmap.c:ext4_inode_bitmap_csum_verify
```
```
In fs/ext4/extents.c (ffffffff8139b47f)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/extents.c:ext4_extent_block_csum
```
```
In fs/ext4/ialloc.c (ffffffff813abca3)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ialloc.c:__ext4_new_inode
  - fs/ext4/ialloc.c:__ext4_new_inode
```
```
In fs/ext4/inode.c (ffffffff813b8e2e)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/inode.c:__ext4_iget
  - fs/ext4/inode.c:__ext4_iget
```
```
In fs/ext4/ioctl.c (ffffffff813c036d)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/ioctl.c:reset_inode_seed
  - fs/ext4/ioctl.c:reset_inode_seed
```
```
In fs/ext4/mmp.c (ffffffff813cc4ab)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/mmp.c:read_mmp_block
  - fs/ext4/mmp.c:write_mmp_block
```
```
In fs/ext4/namei.c (ffffffff813ce421)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_dx_csum
  - fs/ext4/namei.c:ext4_handle_dirty_dirblock
```
```
In fs/ext4/super.c (ffffffff813ed291)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/super.c:ext4_get_dev_journal
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_fill_super
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_group_desc_csum
  - fs/ext4/super.c:ext4_superblock_csum_set
```
```
In fs/ext4/xattr.c (ffffffff813f506f)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
```
In fs/jbd2/commit.c (ffffffff813fe38d)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
  - fs/jbd2/commit.c:jbd2_journal_commit_transaction
```
```
In fs/jbd2/recovery.c (ffffffff814000c5)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
  - fs/jbd2/recovery.c:do_one_pass
```
```
In fs/jbd2/journal.c (ffffffff81404c88)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:journal_get_superblock
  - fs/jbd2/journal.c:jbd2_write_superblock
  - fs/jbd2/journal.c:jbd2_descriptor_block_csum_set
```
```
In fs/ecryptfs/crypto.c (ffffffff814209eb)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/crypto.c:ecryptfs_hash_digest
```
```
In fs/ecryptfs/keystore.c (ffffffff81424758)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - fs/ecryptfs/keystore.c:ecryptfs_write_tag_70_packet
```
```
In security/keys/dh.c (ffffffff814597e0)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/dh.c:__keyctl_dh_compute
```
```
In security/keys/trusted.c (ffffffff8145b465)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/trusted.c:init_sdesc
```
```
In security/keys/encrypted-keys/encrypted.c (ffffffff8145d436)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/keys/encrypted-keys/encrypted.c:calc_hash
```
```
In security/integrity/evm/evm_crypto.c (ffffffff814c9f7e)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - security/integrity/evm/evm_crypto.c:init_desc
```
```
In crypto/shash.c (ffffffff814d3c20)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/shash.c:crypto_init_shash_ops_async
  - crypto/shash.c:shash_default_import
  - crypto/shash.c:shash_default_export
```
```
In crypto/hmac.c (ffffffff814d73d9)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/hmac.c:hmac_init_tfm
```
```
In crypto/drbg.c (ffffffff814e4096)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/drbg.c:drbg_init_hash_kernel
```
```
In crypto/asymmetric_keys/x509_public_key.c (ffffffff814e8334)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/x509_public_key.c:x509_get_sig_params
```
```
In crypto/asymmetric_keys/pkcs7_verify.c (ffffffff814e9677)
Location: include/crypto/hash.h:801
Inline: True
```
```
In crypto/asymmetric_keys/verify_pefile.c (ffffffff814ea00c)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - crypto/asymmetric_keys/verify_pefile.c:pefile_digest_pe
```
```
In lib/digsig.c (ffffffff815681c2)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - lib/digsig.c:digsig_verify
```
```
In arch/x86/power/hibernate.c (ffffffff8191d0b9)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - arch/x86/power/hibernate.c:get_e820_md5
```
```
In net/ipv6/seg6_hmac.c (ffffffff82925196)
Location: include/crypto/hash.h:801
Inline: True
Inline callers:
  - net/ipv6/seg6_hmac.c:seg6_hmac_init
```
</details>
</li>
</ul>

## Differences
