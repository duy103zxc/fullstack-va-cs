# Tu luyện lập trình
Con đường tự học Fullstack và Computer Science của mình. Bao gồm lộ trình, hướng dẫn và tài nguyên.

## Lịch trình & Phương pháp học tập

### Lịch trình

Tuần | Nhiệm vụ | Bài tập & Dự án | Các hướng dẫn cần hoàn thiện
--- | --- | --- | ---
1 | - Ôn tập lại toàn bộ phần cơ bản của HTML/CSS/JS và Rust | Hoàn thành JS30Day & Một dự án Rust | - Danh sách phát của F8 (Đọc từng video một xem có chủ đề nào chưa rõ hoặc chưa biết thì học)<br/>- Soát lại trong The Book xem các điểm kiến thức còn chưa vững, đặc biết là Deref, Trait, Closure và Async 
2 | Chưa có | Chưa có | Chưa có


### Phương pháp
#### Phương pháp ghi nhớ 
Sử dụng [hướng dẫn Janki](https://www.semicolonandsons.com/articles/janki-method-refined) - Đại khái là tích hợp SRS vào để đẩy nhanh quá trình học. Mình cũng đã học được rất nhiều điều từ MIA (Mass Immersion Approach). Bản Backup của Janki:

- [Tổng quan về phương pháp](assets/janki1.md)
- [Một số các hướng dẫn tạo thẻ](assets/janki2.md)


#### Mỗi ngày
- Thực hiện hàng ngày dù ít hay nhiều - Atomic Habits.
- Ghi chú: Về mặt kiến thức cần ghi nhớ, hãy ghi ra một tệp plain-text rồi để thêm vào Anki. 

#### Đọc thêm thật nhiều code
Mình cần đi đọc thêm rất nhiều các dự án trên Github để nạp càng nhiều Input càng tốt, những cách xử lý vấn đề, Functions, cách chia cấu trúc dự án .v.v Lấy hết.

Một số Repo tổng hợp có thể đọc

- [50projects50days](https://github.com/bradtraversy/50projects50days) - 50+ mini web projects sử dụng HTML, CSS & JS 
- [duykhanh471/mia-rs](https://codeberg.org/duykhanh471/mia-rs) - Khu lưu đống Code Rust mình đi lượm trên Github
- [solygambas/rust-projects](https://github.com/solygambas/rust-projects) -  5 small projects to understand Rust core concepts. 

Và có thể đi đọc thêm bất kì các dự án mã nguồn mở nào mình yêu thích hoặc đúng theo kiểu ứng dụng mình muốn làm. Đọc và nhớ ném nó vào Anki nếu thấy có ích!

#### Từ điển lập trình cá nhân
Đây là một cách ngớ ngẩn mà mình tự nghĩ ra. Giả sử, mình làm ứng dụng mà cần xử lý tệp khá nhiều nên luôn cần `read_file()` và `write_file()`, nhưng mình khá là lười học thuộc mấy cái đó nên đóng luôn một thư mục chuyên lưu những Functions mà mình muốn/sẽ/có thể/cần sử dụng.

Khi nào cần thì chỉ cần `Ctrl + C` và `Ctrl + V` là xong.

Ví dụ, mình lưu đống Functions xử lý đọc/ghi tệp trong [idioms/read_and_write.md](https://codeberg.org/duykhanh471/mia-rs/src/branch/main), một tệp Markdown bất kì.

Nó giống như một Documentation nhỏ của riêng mình vậy. Thay vì phải đi tra Google mỗi lần gặp hoặc chờ cho đến khi gặp đủ nhiều lần để nhớ thì có thể làm như thế này hoặc tích hợp với Anki cũng được luôn.

Cập nhật: Mới gần đây khi xem trang chủ của tác giả Janki Method thì tui phát hiện ra được một hướng dẫn tương tự phần này nhưng tốt hơn, đó là ["Code Diary"](https://www.youtube.com/watch?v=tarmCEHfGa0)

Một số gợi ý cho việc nạp Input dưới dạng xem video: 

- [hellerve/programming-talks](https://github.com/hellerve/programming-talks)
- [jamesmunns/awesome-rust-streaming](https://github.com/jamesmunns/awesome-rust-streaming)


#### Thiết kế
> 90% of coding is planning, design, architecture etc, ie. knowing what to code and why rather than the act of physically typing it out.


## Fullstack
Trước tiên mình muốn chạy để làm sản phẩm vì có nhiều ý tưởng.

Mình chưa thử hết cả 3 lộ trình này và thấy nhiều lập trình viên theo nên mình cứ để đây cho bạn chọn, còn mình tự đi theo một hướng khác: 

- [FullstackOpen](https://fullstackopen.com/en/) - Được gợi ý ở bên OSSU
- [The Odin Project](https://www.theodinproject.com/)
- [freecodecamp](https://www.freecodecamp.org)

Thiết bị sử dụng để học: Một Laptop đời thấp cài Linux và VSCode.

Mình muốn cải thiện kĩ năng để sử dụng cả hai cái này.

- Học Linux: Hoàn thành khóa [Linux Journey](https://linuxjourney.com/) & Thực hiện [thử thách](https://www.reddit.com/r/linuxupskillchallenge/) 
- Học VSCode: Đọc Document của VSCode luôn: https://code.visualstudio.com/docs

### HTML, CSS, và JavaScript
#### Cơ bản
Cày cả ba khóa trên F8.

- [HTML và CSS](https://www.youtube.com/playlist?list=PL_-VfJajZj0U9nEXa4qyfB4U5ZIYCMPlz)
- [JavaScript](https://www.youtube.com/playlist?list=PL_-VfJajZj0VgpFpEVFzS5Z-lkXtBe-x5)

Mình đã từng học hết cả 3 phần này nên mình hơi lười học lại và sử dụng LearnXinYMinutes để ôn lại:

- [HTML](https://learnxinyminutes.com/docs/vi-vn/html-vi/) - Bản dịch Tiếng Việt
- [CSS](https://learnxinyminutes.com/docs/css/)
- [JavaScript](https://learnxinyminutes.com/docs/javascript/)

Mình cũng có theo khóa 30DayJS để làm 30 dự án nhỏ trong 30 ngày. Đọc [30 Day Vanilla JS Coding Challenge](https://javascript30.com).

#### Nâng cao

Một số các danh sách phát trên Youtube:

- [Intermediate HTML and CSS Course](https://www.theodinproject.com/paths/full-stack-javascript/courses/intermediate-html-and-css)
- [Advanced HTML and CSS Course](https://www.theodinproject.com/paths/full-stack-javascript/courses/advanced-html-and-css) 
- [Sử dụng JS nâng cao](https://www.theodinproject.com/paths/full-stack-javascript/courses/javascript)
- [Mẹo JavaScript](https://www.youtube.com/playlist?list=PLw0w5s5b9NK4fr9o4uT2xVX199343SPir)

#### TheOdinProject đặc biệt
Đây là một số bài viết khá đặc biệt của họ.

- [Commit Message](assets/commit-msg.md)
- [Giải quyết vấn đề](assets/problem-solving.md)
- [Hiểu thêm về lỗi trong lập trình](assets/understand-error.md)
- [Clean code](assets/clean-code.md)

### JS Framework

### Backend
Mình học Rust. Vì các nguồn Rust không nhiều nên mình sẽ học luôn bằng Tiếng Anh và các nguồn dẫn trong phần này cũng sẽ toàn là Tiếng Anh luôn.

#### Cơ bản
- [Sách Rust](https://doc.rust-lang.org/book/title-page.html) - Mới đọc qua, cần đọc lại các chủ đề còn chưa vững trong tuần đầu tiên của lộ trình
- [rustlings](https://github.com/rust-lang/rustlings) - Đã làm xong từ lâu (Dù ăn gian bỏ qua ba bài)

#### Dự án
- <https://jrdngr.github.io/pngme_book/>
- [too-many-lists](https://rust-unofficial.github.io/too-many-lists)

#### Rust design patterns (intermediate):
- <https://rust-unofficial.github.io/patterns/intro.html>
- <https://www.lurklurk.org/effective-rust/title-page.html>

#### Lifetimes
- <https://github.com/pretzelhammer/rust-blog/blob/master/posts/common-rust-lifetime-misconceptions.md>
- <https://doc.rust-lang.org/nomicon/ownership.html>

#### Xử lý lỗi
- <https://lexi-lambda.github.io/blog/2019/11/05/parse-don-t-validate/>
- <https://sabrinajewson.org/blog/errors>  (modular errors)
- <https://fsharpforfunandprofit.com/posts/recipe-part2/>  (railway oriented programming)


#### Các chủ đề riêng biệt
- [Architecture](https://matklad.github.io/2021/09/05/Rust100k.html):
- [Async](https://rust-lang.github.io/async-book/01_getting_started/01_chapter.html) - Sau đó mới qua [Tokio](https://tokio.rs/tokio/tutorial)

#### Tài nguyên khác
- [The Little Book of Rust Macros](https://veykril.github.io/tlborm): Everything you need to know about macros.
- [Learn Rust Page](https://www.rust-lang.org/learn): Index for Rust's documentation page. Includes things such as the Edition Guide, Cargo Book, etc.
- [Awesome Rust](https://github.com/kud1ing/awesome-rust):  A huge list of the best crates and tools you could possibly think of!
- [Are we ___ yet](https://github.com/UgurcanAkkok/AreWeRustYet)
- [Rust FFI Omnibus](https://jakegoulding.com/rust-ffi-omnibus) - How to use Rust code in other languages
- [Rust Cheatsheet](https://cheats.rs/):- List of a bunch of common Rust knowledge. 

#### Unfair quizzes
- <https://dtolnay.github.io/rust-quiz/>
- <https://boxyuwu.github.io/rust-quiz/index.html>

#### Song song vs Rust
- [Backend Development với API của Freecodecamp](https://www.freecodecamp.org/learn/back-end-development-and-apis/) - Có cả Relational Database với các thứ như `npm` và vân vân mây mây.

#### **Học cả NodeJS và ExpressJS**

Thấy có khá nhiều dự án làm bằng cái này nên để thêm vào thôi

Danh sách phát của F8: [NodeJS và ExpressJS](https://www.youtube.com/playlist?list=PL_-VfJajZj0VatBpaXkEHK_UPHL7dW6I3)


### Học SQL và PostgreSQL
Mình sẽ học gần như toàn bộ phần này ở dưới lộ trình [Khoa học máy tính](#5-cơ-sở-dữ-liệu). Còn lại là xử lý PostgreSQL.


### Xây dựng dự án và Deploy
Tự chọn một ý tưởng để làm Fullstack.

Các dự án được làm sẽ được liệt kê ra sau.

### Bổ sung hành trang đi làm

#### Phỏng vấn

Interview Prep của Freecodecamp: <https://www.freecodecamp.org/learn/coding-interview-prep>

#### Học thiết kế hệ thống

- System Design Primer: <https://github.com/donnemartin/system-design-primer>
- System Design Interview: <https://www.youtube.com/c/SystemDesignInterview>

#### Data Visualization với D3.js

FreeCodeCamp: <https://www.freecodecamp.org/learn/data-visualization/>

#### AWS, Microservices, Docker
Đống này tôi không định học theo, để đặt nội dung trước thôi.

- Khóa trên Udemy - Ultimate AWS Certified Developer Associate 2022: <https://www.udemy.com/course/aws-certified-developer-associate-dva-c01/>
- Khóa trên Udemy - Microservices with Node JS and React: <https://www.udemy.com/course/microservices-with-node-js-and-react/>
- Docker Fundamentals: <https://learn.cantrill.io/p/docker-fundamentals>
- Dive into Docker: <https://diveintodocker.com/>


## Khoa học máy tính
Đường dẫn bắt đầu: [Teach Yourself Computer Science (https://teachyourselfcs.com/)](https://teachyourselfcs.com/)

**CẬP NHẬT:** Mình thử tìm hiểu thêm thì thấy có khá nhiều vấn đề trong cách định hướng nên quyết định làm thêm mục dưới. Gợi ý của TYCS khá cô đọng, có đôi lúc bị nâng cao quá và ở một số phần mình thấy vẫn chưa cung cấp đủ các phần khác mà có thể bạn cần.

Tham gia cộng đồng tự học trên Discord để cùng trao đổi: [Khoa học máy tính!](https://discord.gg/x93EE354PB)

### 1. Programming
Do bị loạn khi đọc sách nên t đi tìm một hướng tiếp cận khác, là sử dụng lộ trình được một người làm sẵn để học theo, có thể học song song cả bài giảng CS61A lẫn sách (Sẽ được đề cập thêm ở trong tài liệu được để đường dẫn ở đây): [Structure and Interpretation of Computer Programs (https://romanbird.github.io/sicp/)](https://romanbird.github.io/sicp/) (Bao gồm cả Lab với Homework luôn). Lưu ý là sẽ sử dụng Scheme

### 2. Computer Architecture
Nếu mọi người muốn học thông qua bài giảng trên Youtube thì có một danh sách phát, dưới dạng Recording lại thôi: [Computer Systems: A programmer's Perspective](https://www.youtube.com/playlist?list=PLyboo2CCDSWnhzzzzDQ3OBPrRiIjl-aIE)

Một Repository hiếm hoi mà ổn cho cuốn CS:APP: [Zhenye-Na/CSAPP-Labs](https://github.com/Zhenye-Na/CSAPP-Labs)

Có một ông trong phần bình luận trên Youtube của bài giảng gợi ý:

For anybody that doesn't want the watch the entire series and have some programming background the most worth while lectures are:

- Lecture 10: Program Optimization,
- Lecture 16: System Level IO
- Lecture 20: Dynamic Memory Allocation Advanced Concepts
- Lecture 23: Concurrent Programming

### 3. Data Structure and Algorithms
Chuyển qua về việc học DSA, cá nhân t thử nhìn qua khóa trên Youtube thì chất lượng khá thấp (Khóa trên Youtube là quay lại bài giảng với sách thì chưa đọc). T tìm cái gì đó dễ tiếp cận với các video được chia bite-sized để dễ tiếp thu thì có bộ video bài giảng của đại học Stanford về môn này, thiên về hướng hiểu thuật toán hơn là sử dụng một ngôn ngữ cụ thể:

- [Algorithms 1](https://www.youtube.com/playlist?list=PLXFMmlk03Dt7Q0xr1PIAriY5623cKiH7V)
- [Algorithms 2](https://www.youtube.com/playlist?list=PLXFMmlk03Dt5EMI2s2WQBsLsZl7A5HEK6)
Lấy slide bài giảng với các thông tin khác trên repo này: [AlessandroCorradini/Stanford-University-Algorithms-Design-and-Analysis](https://github.com/AlessandroCorradini/Stanford-University-Algorithms-Design-and-Analysis)

Luyện tập thì: [Solve Algorithms Code Challenges](https://www.hackerrank.com/domains/algorithms) (Hoặc có thể dùng Leetcode nhưng Leetcode có vẻ chuyên cho việc đi phỏng vấn hơn).


### 4. Toán
Về phần học toán, t đang khá phân vân nên là đây mới là định hướng thôi

- Phần liên quan nhất với CS là toán rời rạc, nên t sẽ bắt đầu trước từ cái này: <https://cims.nyu.edu/~regev/teaching/discrete_math_fall_2005/dmbook.pdf>
- Chuyển qua học đại số tuyến tính (Linear Algebra): [Essence of linear algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab).

Còn một gợi ý khác là học cuốn Math for Computer Science nhưng nó hơi nâng cao so với t nên bỏ qua

### 5. Cơ sở dữ liệu
Gợi ý của bên trang hướng dẫn là xem bài giảng CS186: [CS186Berkeley](https://www.youtube.com/@CS186Berkeley/videos)

Vấn đề là định hướng học từ đâu và học thế nào thì không thấy đề cập trong trang, nên t sẽ bổ sung thêm là:

- Đọc Repo này trên Github để tìm Slide bài giảng các thứ: [PKUFlyingPig/CS186: Learning materials for UCB CS186](https://github.com/PKUFlyingPig/CS186)
- Tham khảo thêm lộ trình học khóa này (2024): [cs186berkeley](https://cs186berkeley.net/)
- [Các dự án trong khóa học: CS186 Projects (https://cs186.gitbook.io/project)](https://cs186.gitbook.io/project)


Còn một số phần khác như Hệ điều hành hay Distributed System thì học sau và sẽ được cập nhật lại

**Đi xa hơn nữa, học sâu hơn về các định hướng cụ thể**

Ban đầu mình có theo OSSU nhưng nội dung lộ trình khá là nặng, nhưng mình vẫn gợi ý theo Advanced CS của bên họ cho từng mảng mà bạn muốn theo: [ossu/computer-science](https://github.com/ossu/computer-science?tab=readme-ov-file#advanced-cs)


## Các chủ đề khác mà mình muốn học

### LearnXinYminutes
Các phần này đều là bản dịch Tiếng Việt
- [JSON](https://learnxinyminutes.com/docs/vi-vn/json-vi/)
- [Markdown](https://learnxinyminutes.com/docs/markdown/) - Không biết là còn phần gì về Markdown cơ bản mà mình chưa biết không.
- [TypeScript](https://learnxinyminutes.com/docs/vi-vn/typescript-vi/)
- [Git](https://learnxinyminutes.com/docs/vi-vn/git-vi/) - Không biết nhiều về Git khi sử dụng thông qua giao diện dòng lệnh.


Một số danh sách phát trên Youtube

- [Con đường Lập Trình Viên](https://www.youtube.com/playlist?list=PLw0w5s5b9NK5fDx409WXgT06Zm4P83yiA)
- [Microservices backend](https://www.youtube.com/playlist?list=PLw0w5s5b9NK5SUfrJ8rjIMYitT9K8WB8W)