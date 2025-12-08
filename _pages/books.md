---
layout: default
title: "Books"
---

<div class="d-flex align-items-center justify-content-between mb-3">
  <h1 class="mb-0">Books · Sách mình đã đọc / đang đọc</h1>
  <span class="badge-soft">Reading to grow 📚</span>
</div>

<p class="text-muted-soft mb-4">
  Mình tin rằng sách là một trong những “kênh mentor” rẻ và hiệu quả nhất.
  Ở đây mình ghi lại một vài cuốn sách ảnh hưởng nhiều đến cách mình suy nghĩ về
  <strong>cuộc sống, kinh doanh và con người</strong>.
</p>

<style>
  .book-card {
    background: var(--bg-card-soft, rgba(15, 23, 42, 0.96));
    border-radius: 1.2rem;
    border: 1px solid var(--border-soft, rgba(148, 163, 184, 0.18));
    padding: 1.3rem 1.2rem 1.35rem 1.2rem;
    height: 100%;
    display: flex;
    flex-direction: row;
    gap: 1rem;
    text-decoration: none;
    color: inherit;
    transition: transform 0.18s ease, box-shadow 0.18s ease, border-color 0.18s ease,
      background 0.18s ease;
    box-shadow: 0 14px 32px rgba(15, 23, 42, 0.85);
  }

  .book-card:hover {
    transform: translateY(-4px) scale(1.01);
    box-shadow: 0 22px 60px rgba(15, 23, 42, 0.95);
    border-color: rgba(56, 189, 248, 0.55);
    background: radial-gradient(circle at 0 0, rgba(56, 189, 248, 0.12), transparent 55%),
      var(--bg-card-soft, rgba(15, 23, 42, 0.98));
  }

  .book-cover {
    width: 72px;
    min-width: 72px;
    height: 104px;
    border-radius: 0.8rem;
    object-fit: cover;
    box-shadow: 0 10px 26px rgba(15, 23, 42, 0.95);
  }

  .book-meta-title {
    font-size: 1rem;
    font-weight: 600;
    margin-bottom: 0.1rem;
  }

  .book-meta-author {
    font-size: 0.85rem;
    color: var(--text-muted, #9ca3af);
    margin-bottom: 0.35rem;
  }

  .book-tag {
    display: inline-flex;
    align-items: center;
    gap: 0.25rem;
    font-size: 0.75rem;
    padding: 0.15rem 0.55rem;
    border-radius: 999px;
    border: 1px solid rgba(148, 163, 184, 0.4);
    color: var(--text-muted, #9ca3af);
    margin-right: 0.25rem;
    margin-bottom: 0.25rem;
  }

  .book-tag::before {
    content: "•";
    font-size: 0.8rem;
  }

  .book-desc {
    font-size: 0.87rem;
    color: var(--text-main, #e5e7eb);
    margin-bottom: 0.4rem;
  }

  .book-link-hint {
    font-size: 0.8rem;
    color: var(--accent, #38bdf8);
  }

  @media (max-width: 768px) {
    .book-card {
      flex-direction: row;
    }
  }
</style>

<div class="row g-3 mb-4">

  <!-- Book 1 -->
  <div class="col-md-4 col-sm-6">
    <a
      class="book-card"
      href="#"
      target="_blank"
      rel="noopener noreferrer"
    >
      <img
        src="{{ site.baseurl }}/assets/images/book-alchemist.jpg"
        alt="Nhà giả kim"
        class="book-cover"
      />
      <div>
        <div class="book-meta-title">Nhà giả kim</div>
        <div class="book-meta-author">Paulo Coelho</div>
        <p class="book-desc">
          Câu chuyện về hành trình đi tìm “kho báu” của Santiago, nhưng kho báu thật sự
          lại nằm ở việc hiểu chính mình, hiểu ước mơ và dám đi đến cùng.
        </p>
        <div class="mb-1">
          <span class="book-tag">Tiểu thuyết truyền cảm hứng</span>
          <span class="book-tag">Tư duy cuộc sống</span>
        </div>
        <div class="book-link-hint">→ Xem chi tiết cuốn sách</div>
      </div>
    </a>
  </div>

  <!-- Book 2 -->
  <div class="col-md-4 col-sm-6">
    <a
      class="book-card"
      href="#"
      target="_blank"
      rel="noopener noreferrer"
    >
      <img
        src="{{ site.baseurl }}/assets/images/book-dac-nhan-tam.jpg"
        alt="Đắc nhân tâm"
        class="book-cover"
      />
      <div>
        <div class="book-meta-title">Đắc nhân tâm</div>
        <div class="book-meta-author">Dale Carnegie</div>
        <p class="book-desc">
          Một trong những cuốn sách kinh điển về nghệ thuật giao tiếp,
          thấu hiểu người khác và xây dựng mối quan hệ tích cực trong học tập, công việc lẫn cuộc sống.
        </p>
        <div class="mb-1">
          <span class="book-tag">Giao tiếp</span>
          <span class="book-tag">Tâm lý</span>
        </div>
        <div class="book-link-hint">→ Xem chi tiết cuốn sách</div>
      </div>
    </a>
  </div>

  <!-- Book 3 -->
  <div class="col-md-4 col-sm-6">
    <a
      class="book-card"
      href="#"
      target="_blank"
      rel="noopener noreferrer"
    >
      <img
        src="{{ site.baseurl }}/assets/images/book-good-to-great.jpg"
        alt="Từ tốt đến vĩ đại"
        class="book-cover"
      />
      <div>
        <div class="book-meta-title">Từ tốt đến vĩ đại</div>
        <div class="book-meta-author">Jim Collins</div>
        <p class="book-desc">
          Nghiên cứu nổi tiếng về lý do vì sao một số công ty có thể “bật lên”
          và duy trì thành công bền vững, trong khi những công ty khác thì không.
        </p>
        <div class="mb-1">
          <span class="book-tag">Kinh doanh</span>
          <span class="book-tag">Chiến lược</span>
        </div>
        <div class="book-link-hint">→ Xem chi tiết cuốn sách</div>
      </div>
    </a>
  </div>

</div>

---

## 🎯 Mục tiêu đọc sách

Mục tiêu của mình là:

- Mỗi năm đọc ít nhất <strong>10 cuốn sách</strong> liên quan đến kinh doanh, tâm lý, kỹ năng mềm
- Không chỉ “đọc cho xong”, mà:
  - Ghi lại tóm tắt ngắn gọn
  - Chọn ra 3–5 ý chính áp dụng được vào thực tế
  - Liên tục cập nhật lại trang **Books** này như một “nhật ký đọc” nhỏ

> Sau này, mỗi cuốn sách có thể đi kèm 1 bài blog chi tiết hơn – chia sẻ về những gì mình học được
> và cách mình áp dụng vào cuộc sống sinh viên Quản trị Kinh doanh tại FTU.
