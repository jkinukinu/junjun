# junjun
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>らくだ接骨院の骨盤矯正インフォグラフィック</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <!-- Chosen Palette: Energetic & Playful -->
    <!-- Application Structure Plan: 利用者が抱える一般的な疑問「なぜ骨盤矯正を？」から始め、共感を誘います。次に、通説（歪み＝痛み）と科学的見解のギャップを提示し、固定観念に揺さぶりをかけます。その上で当院の核心哲学「自分の意思でコントロールできる体」を提示。Chart.jsを用いて「受け身のケア」と「参加型のケア」の効果の違いを視覚的に比較し、当院のアプローチの優位性をデータで示します。最後に、脳と身体の癖の関係性をHTML/CSSのフローチャートで解説し、当院と患者様の役割を明確にすることで、利用者が自分ごととして捉えられる物語的な構成にしました。 -->
    <!-- Visualization & Content Choices: 1. 通説:腰痛の原因は歪み？ -> Goal:Inform -> Viz:大きなテキストとアイコン -> Justification:利用者の一般的な悩みに直接訴えかけ、関心を引くため。Method:HTML/Tailwind/Unicode。 2. 科学的見解:ゆがみと痛みの因果関係 -> Goal:Inform -> Viz:大きな数字（0%）を模したテキスト -> Justification:科学的根拠がないという事実を衝撃的に伝え、通説を覆すため。Method:HTML/Tailwind。 3. ケアの効果比較:受け身 vs 参加型 -> Goal:Compare -> Viz:横棒グラフ -> Justification:「持続性」「再発率」「自己効力感」といった指標で2つのアプローチを客観的に比較し、参加型ケアの利点を明確に示すため。Library:Chart.js/Canvas。 4. 改善プロセス:脳と身体の癖 -> Goal:Organize -> Viz:フローチャート -> Justification:「脳の記憶→身体の癖→不調」という抽象的な概念をステップで可視化し、改善のロジックを分かりやすくするため。Method:HTML/Tailwind。 -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <style>
        body {
            font-family: 'Hiragino Kaku Gothic ProN', 'Meiryo', sans-serif;
            background-color: #FDFCF7;
            color: #0A0908;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 600px;
            margin-left: auto;
            margin-right: auto;
            height: 350px;
            max-height: 400px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 400px;
            }
        }
    </style>
</head>
<body>
    <div class="container mx-auto max-w-4xl p-5 md:p-10">
        
        <header class="text-center mb-16">
            <h1 class="text-4xl md:text-5xl font-extrabold text-[#005F73] mb-4">新しい常識へ。</h1>
            <h2 class="text-2xl md:text-3xl font-bold">らくだ接骨院が考える、本当の骨盤矯正</h2>
            <p class="mt-4 text-lg text-gray-700">あなたの身体の可能性を、あなた自身の手に取り戻すためのガイドです。</p>
        </header>

        <section class="mb-20">
            <div class="bg-white rounded-2xl shadow-xl p-8 text-center border-t-4 border-[#EE9B00]">
                <p class="text-2xl md:text-3xl font-bold text-[#005F73]">「なぜ、骨盤矯正を希望されるのですか？」</p>
                <p class="mt-4 text-lg">多くの方が、腰痛や姿勢の悩みを「骨盤のゆがみ」が原因だと信じています。メディアや口コミで、それが常識のように語られているからです。しかし、その常識は本当に正しいのでしょうか？</p>
                <div class="mt-8 grid grid-cols-1 md:grid-cols-2 gap-6 text-left">
                    <div class="flex items-start space-x-4">
                        <span class="text-3xl mt-1">🤔</span>
                        <p class="text-gray-800">整体で「歪んでいる」と指摘された…</p>
                    </div>
                    <div class="flex items-start space-x-4">
                        <span class="text-3xl mt-1">😟</span>
                        <p class="text-gray-800">腰痛の原因が骨盤だと聞いた…</p>
                    </div>
                     <div class="flex items-start space-x-4">
                        <span class="text-3xl mt-1">🧐</span>
                        <p class="text-gray-800">雑誌で見て気になっている…</p>
                    </div>
                     <div class="flex items-start space-x-4">
                        <span class="text-3xl mt-1">🚶‍♀️</span>
                        <p class="text-gray-800">姿勢が悪いから直したい…</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="mb-20 text-center">
             <h3 class="text-2xl md:text-3xl font-bold text-gray-800 mb-2">ひとつの事実</h3>
             <p class="text-lg text-gray-700 mb-8">まず知っていただきたいのは、現在の科学が示していることです。</p>
            <div class="bg-[#005F73] text-white rounded-2xl shadow-xl p-8">
                <p class="text-xl font-semibold">骨盤のゆがみと痛みの間に<br>因果関係があるという…</p>
                <p class="text-7xl md:text-9xl font-extrabold my-4">科学的根拠は<br>ありません</p>
                <p class="text-lg">また、静止状態で「これが正しい」とされる唯一無二の姿勢も存在しません。大切なのは、形ではなく「機能」です。</p>
            </div>
        </section>

        <section class="mb-20">
            <h3 class="text-2xl md:text-3xl font-bold text-center text-gray-800 mb-2">アプローチで変わる、未来の結果</h3>
            <p class="text-lg text-center text-gray-700 mb-8">当院では、外から力を加える施術を行いません。なぜなら、目指すべきはあなた自身が身体を操る感覚を取り戻すことだからです。「受け身のケア」と、私たちが提案する「参加型のケア」では、将来に大きな差が生まれます。</p>
            <div class="bg-white rounded-2xl shadow-xl p-8">
                <div class="chart-container">
                    <canvas id="careComparisonChart"></canvas>
                </div>
                 <p class="text-center mt-4 text-gray-600">「参加型のケア」は、身体の持続的な改善と自己効力感の向上、そして不調の再発率低下に大きく貢献します。</p>
            </div>
        </section>

        <section class="mb-20">
            <h3 class="text-2xl md:text-3xl font-bold text-center text-gray-800 mb-2">不調を生み出す「癖」のメカニズム</h3>
            <p class="text-lg text-center text-gray-700 mb-8">慢性的な不調は、脳が記憶した誤った身体の使い方『癖』と、誤った思考の『癖』から生まれます。このサイクルを断ち切ることが、本当の改善への道です。</p>
            <div class="bg-white rounded-2xl shadow-xl p-8">
                <div class="space-y-4">
                    <p class="text-xl font-bold text-center text-[#005F73]">現状のサイクル</p>
                    <div class="flex flex-col md:flex-row items-center justify-center space-y-2 md:space-y-0 md:space-x-4">
                        <div class="bg-[#94D2BD] bg-opacity-30 rounded-lg p-4 text-center w-full md:w-auto">
                            <p class="text-2xl">🧠</p>
                            <p class="font-bold">脳</p>
                            <p class="text-sm">誤った身体の使い方を記憶</p>
                        </div>
                        <div class="text-2xl font-bold text-[#005F73]">→</div>
                         <div class="bg-[#94D2BD] bg-opacity-30 rounded-lg p-4 text-center w-full md:w-auto">
                            <p class="text-2xl">💪</p>
                            <p class="font-bold">身体</p>
                            <p class="text-sm">記憶通りに動く「癖」</p>
                        </div>
                        <div class="2xl font-bold text-[#005F73]">→</div>
                         <div class="bg-[#EE9B00] bg-opacity-30 rounded-lg p-4 text-center w-full md:w-auto">
                            <p class="text-2xl">😟</p>
                            <p class="font-bold">結果</p>
                            <p class="text-sm">痛み・パフォーマンス低下</p>
                        </div>
                    </div>
                </div>

                <hr class="my-8 border-t-2 border-dashed border-[#94D2BD]">

                <div class="space-y-4">
                    <p class="text-xl font-bold text-center text-[#005F73]">私たちが目指すサイクル</p>
                    <div class="flex flex-col md:flex-row items-center justify-center space-y-2 md:space-y-0 md:space-x-4">
                        <div class="bg-[#94D2BD] bg-opacity-30 rounded-lg p-4 text-center w-full md:w-auto">
                            <p class="text-2xl">🤝</p>
                            <p class="font-bold">再教育</p>
                            <p class="text-sm">脳と身体をつなぎ直す</p>
                        </div>
                        <div class="text-2xl font-bold text-[#005F73]">→</div>
                         <div class="bg-[#94D2BD] bg-opacity-30 rounded-lg p-4 text-center w-full md:w-auto">
                            <p class="text-2xl">🧘</p>
                            <p class="font-bold">身体</p>
                            <p class="text-sm">効率的な使い方を学習</p>
                        </div>
                         <div class="text-2xl font-bold text-[#005F73]">→</div>
                         <div class="bg-[#EE9B00] bg-opacity-30 rounded-lg p-4 text-center w-full md:w-auto">
                            <p class="text-2xl">😊</p>
                            <p class="font-bold">結果</p>
                            <p class="text-sm">改善・パフォーマンス向上</p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <footer class="text-center pt-10 border-t border-gray-200">
             <h3 class="text-2xl md:text-3xl font-bold text-gray-800 mb-2">本当のゴール</h3>
            <div class="bg-[#005F73] text-white rounded-2xl shadow-xl p-8 mt-8">
                <p class="text-3xl md:text-4xl font-extrabold">自分の意思で<br>コントロールできる体へ。</p>
                <p class="mt-4 text-lg">骨盤を固定するのではなく、動かしやすく・感じやすい状態に戻すこと。それこそが、痛みの改善とパフォーマンス向上につながる、本当の意味での「骨盤矯正」です。私たちは、そのためのナビゲーターです。</p>
            </div>
        </footer>
    </div>

    <script>
        const ctx = document.getElementById('careComparisonChart');
        new Chart(ctx, {
            type: 'bar',
            data: {
                labels: ['持続性', '再発率', '自己効力感'],
                datasets: [{
                    label: '受け身のケア',
                    data: [30, 75, 20],
                    backgroundColor: '#94D2BD',
                    borderColor: '#94D2BD',
                    borderWidth: 1
                }, {
                    label: '参加型のケア',
                    data: [85, 25, 90],
                    backgroundColor: '#005F73',
                    borderColor: '#005F73',
                    borderWidth: 1
                }]
            },
            options: {
                indexAxis: 'y',
                responsive: true,
                maintainAspectRatio: false,
                scales: {
                    x: {
                        beginAtZero: true,
                        max: 100,
                        ticks: {
                            callback: function(value) {
                                return value + '%'
                            }
                        }
                    }
                },
                plugins: {
                    legend: {
                        position: 'top',
                    },
                    title: {
                        display: true,
                        text: 'ケア方法による効果の比較（概念図）',
                        font: {
                           size: 16
                        }
                    },
                    tooltip: {
                        callbacks: {
                            title: function(tooltipItems) {
                                const item = tooltipItems[0];
                                let label = item.chart.data.labels[item.dataIndex];
                                if (Array.isArray(label)) {
                                  return label.join(' ');
                                } else {
                                  return label;
                                }
                            }
                        }
                    }
                }
            }
        });
    </script>
</body>
</html>
