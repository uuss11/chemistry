<!DOCTYPE html><html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <title>اختبار الفصول 4 - 5 - 6</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <script src="hh.js" defer></script>
  <script defer>
    document.addEventListener("DOMContentLoaded", () => {
      const quizForm = document.getElementById("quizForm");
      const questionsContainer = document.getElementById("questions");
      const resultBox = document.getElementById("result");
      const scoreDisplay = document.getElementById("score");
      const sendBtn = document.getElementById("sendBtn");
      const stars = document.getElementById("stars");
      const feedback = document.getElementById("feedback");let total = questions.length;
  let answered = 0;
  let correct = 0;

  questions.forEach((q, idx) => {
    const div = document.createElement("div");
    div.className = "mb-4 p-4 border rounded-lg bg-gray-50";

    const qNum = idx + 1;
    const questionHTML = `<p class="font-semibold">${qNum}. ${q.question}</p>`;

    let answersHTML = "";
    const name = `q${qNum}`;

    if (q.type === "tf") {
      answersHTML = `
        <label><input type="radio" name="${name}" value="صح"> صح</label>
        <label class="ml-4"><input type="radio" name="${name}" value="خطأ"> خطأ</label>
      `;
    } else if (q.type === "mc") {
      const options = [...q.options, q.correct];
      options.sort(() => Math.random() - 0.5); // Shuffle options
      answersHTML = options.map(opt => `
        <label class="block">
          <input type="radio" name="${name}" value="${opt}"> ${opt}
        </label>
      `).join("");
    }

    div.innerHTML = questionHTML + answersHTML;
    questionsContainer.appendChild(div);

    // منع التغيير بعد الاختيار
    div.addEventListener("change", (e) => {
      if (e.target.name === name) {
        const inputs = div.querySelectorAll(`input[name='${name}']`);
        inputs.forEach(input => input.disabled = true);
        answered++;
        if (e.target.value === q.correct) correct++;
      }
    });
  });

  document.getElementById("submitBtn").onclick = () => {
    const score = Math.round((correct / total) * 100);
    scoreDisplay.textContent = score;
    resultBox.classList.remove("hidden");

    const name = localStorage.getItem("studentName") || "طالب بدون اسم";

    stars.addEventListener("change", () => {
      const msg = `📚 تقييم اختبار 4-5-6\n👤 الاسم: ${name}\n🎯 الدرجة: ${score}/100\n⭐ التقييم: ${stars.value}\n📝 رأي: ${feedback.value || "بدون"}`;
      const encoded = encodeURIComponent(msg);
      sendBtn.href = `https://t.me/share/url?url=t.me/lJJ2l&text=${encoded}`;
    });
  };
});

  </script>
</head>
<body class="bg-gray-100 p-4 text-right">
  <div class="max-w-3xl mx-auto bg-white p-6 rounded-xl shadow-lg">
    <h1 class="text-2xl font-bold text-center text-blue-700 mb-6">اختبار كيمياء - الفصول 4، 5، 6</h1>
    <form id="quizForm">
      <div id="questions" class="space-y-4"></div>
      <button id="submitBtn" type="button" class="mt-6 w-full bg-blue-600 text-white py-2 rounded-lg hover:bg-blue-700">
        عرض النتيجة
      </button>
    </form><div id="result" class="hidden mt-6 space-y-4">
  <div class="text-xl font-bold text-green-600">درجتك: <span id="score"></span>/100</div>

  <label class="block font-semibold">قيم الموقع من 1 إلى 10 نجوم:</label>
  <select id="stars" class="w-full border rounded-lg p-2">
    <option value="">-- اختر عدد النجوم --</option>
    <option value="★">★</option>
    <option value="★★">★★</option>
    <option value="★★★">★★★</option>
    <option value="★★★★">★★★★</option>
    <option value="★★★★★">★★★★★</option>
    <option value="★★★★★★">★★★★★★</option>
    <option value="★★★★★★★">★★★★★★★</option>
    <option value="★★★★★★★★">★★★★★★★★</option>
    <option value="★★★★★★★★★">★★★★★★★★★</option>
    <option value="★★★★★★★★★★">★★★★★★★★★★</option>
  </select>

  <textarea id="feedback" rows="3" placeholder="اكتب رأيك (اختياري)" class="w-full border rounded-lg p-2"></textarea>

  <a id="sendBtn" target="_blank" class="block w-full bg-green-600 text-white text-center py-2 rounded-lg hover:bg-green-700">
    ارسال التقييم إلى التليجرام
  </a>
</div>

  </div>
</body>
</html>
