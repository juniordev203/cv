<script lang="ts" setup>
import { Cake, Mail, MapPin, Phone, Facebook, Github } from 'lucide-vue-next'
</script>

<template>
    <div class="px-64">
        <header class="flex mb-8">
            <div class="w-72">
                <img src="/assets/images/avatar.jpg" alt="">
            </div>
            <div class="w-full bg-gray-200 justify-center items-center">
                <div class="text-center mx-12 pt-6 pb-2 border-black border-b-2">
                    <p class="text-2xl font-extrabold">Phạm Huy Hoàng</p>
                    <p class="text-lg font-bold">Intern Frontend Developer</p>
                </div>

                <div class="px-8 pt-2 flex flex-wrap items-center justify-center">
                    <div class="flex items-center space-x-2 mb-2 mr-4">
                        <svg class="w-5 h-5 text-black" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                            xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z">
                            </path>
                        </svg>
                        <span class="text-sm text-black">11/09/2003</span>
                    </div>

                    <div class="flex items-center space-x-2 mb-2 mr-4">
                        <svg class="w-5 h-5 text-black" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                            xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z">
                            </path>
                        </svg>
                        <span class="text-sm text-black">huyhoangpham8460@gmail.com</span>
                    </div>

                    <div class="flex items-center space-x-2 mb-2 mr-4">
                        <svg class="w-5 h-5 text-black" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                            xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.827 0l-4.244-4.243a8 8 0 1111.314 0z">
                            </path>
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M15 11a3 3 0 11-6 0 3 3 0 016 0z"></path>
                        </svg>
                        <span class="text-sm text-black">Thanh Xuân, Hà Nội</span>
                    </div>

                    <div class="flex items-center space-x-2 mb-2 mr-4">
                        <svg class="w-5 h-5 text-black" fill="none" stroke="currentColor" viewBox="0 0 24 24"
                            xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                                d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z">
                            </path>
                        </svg>
                        <span class="text-sm text-black">0367435069</span>
                    </div>

                    <div class="flex items-center space-x-2 mb-2 mr-4">
                        <svg class="w-5 h-5 text-black" fill="currentColor" viewBox="0 0 24 24"
                            xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z" />
                        </svg>
                        <span class="text-sm text-black">Huy Hoàng</span>
                    </div>

                    <div class="flex items-center space-x-2 mb-2">
                        <svg class="w-5 h-5 text-black" fill="currentColor" viewBox="0 0 24 24"
                            xmlns="http://www.w3.org/2000/svg">
                            <path
                                d="M12 .297c-6.63 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.385.6.113.82-.258.82-.577 0-.285-.01-1.04-.015-2.04-3.338.724-4.042-1.61-4.042-1.61C4.422 18.07 3.633 17.7 3.633 17.7c-1.087-.744.084-.729.084-.729 1.205.084 1.838 1.236 1.838 1.236 1.07 1.835 2.809 1.305 3.495.998.108-.776.417-1.305.76-1.605-2.665-.3-5.466-1.332-5.466-5.93 0-1.31.465-2.38 1.235-3.22-.135-.303-.54-1.523.105-3.176 0 0 1.005-.322 3.3 1.23.96-.267 1.98-.399 3-.405 1.02.006 2.04.138 3 .405 2.28-1.552 3.285-1.23 3.285-1.23.645 1.653.24 2.873.12 3.176.765.84 1.23 1.91 1.23 3.22 0 4.61-2.805 5.625-5.475 5.92.42.36.81 1.096.81 2.22 0 1.606-.015 2.896-.015 3.286 0 .315.21.69.825.57C20.565 22.092 24 17.592 24 12.297c0-6.627-5.373-12-12-12" />
                        </svg>
                        <span class="text-sm text-black">juniordev203</span>
                    </div>
                </div>
            </div>
        </header>
        <main class="px-11">
            <div class="mb-8">
                <h3 class="mb-3 text-xl font-bold">Giới thiệu</h3>
                <li>Áp dụng kiến thức đã học vào thực tế, làm việc đúng với đam mê của bản thân. Mong muốn tìm kiếm được
                    công
                    việc phù hợp và phát triển.</li>
                <li>Là một người năng động, chăm chỉ và nỗ lực trong công việc. Trong quá trình thực tập cố gắng tích
                    lũy kiến thức và
                    kỹ năng, mục tiêu trở thành nhân viên chính thức của công ty.
                </li>
            </div>
            <div class="mb-8">
                <div class="mb-3">
                    <div class="flex items-center">
                        <div class="w-max flex">
                            <div class="w-48 bg-black text-white py-2 pl-4 font-bold">
                                Học vấn
                            </div>
                            <div
                                class="w-0 h-0 border-t-[20px] border-t-transparent border-b-[20px] border-b-transparent border-l-[16px] border-l-black">
                            </div>
                        </div>
                        <div class="w-full">
                            <div class="-ml-1 h-[3px] bg-black"></div>
                        </div>
                    </div>
                </div>
                <div class="flex justify-between">
                    <p class="font-bold">Trường Đại học Kinh tế Quốc dân</p>
                    <p class="font-bold">Công nghệ thông tin</p>
                    <p>9/2021 - Hiện tại</p>
                </div>
            </div>
            <div class="mb-8">
                <div class="mb-3">
                    <div class="flex items-center">
                        <div class="w-max flex">
                            <div class="w-48 bg-black text-white py-2 pl-4 font-bold">
                                Kinh nghiệm làm việc
                            </div>
                            <div
                                class="w-0 h-0 border-t-[20px] border-t-transparent border-b-[20px] border-b-transparent border-l-[16px] border-l-black">
                            </div>
                        </div>
                        <div class="w-full">
                            <div class="-ml-1 h-[3px] bg-black"></div>
                        </div>
                    </div>
                </div>
                <div class="flex justify-between mb-2">
                    <p class="font-bold">TEAM</p>
                    <p class="font-bold">Fontend Developer</p>
                    <p>2/2024 - Hiện tại</p>
                </div>
                <div>
                    <p>
                        Thành viên thiết kế và phát triển giao diện website<br>
                        Frontend: Angular<br>
                        Backend: C#, .NET Core<br>
                        Database: Mysql<br>
                        Doc API: Swagger<br>
                        Số lượng thành viên: 4<br>
                        Chức năng chính: quản lý tuyển sinh sau đại học<br>
                        Hoạt động xoay quay hồ sơ nhập học cao học<br>
                        Mỗi hồ sơ sẽ trải qua các bước:<br>
                        - Nhập hồ sơ, kiểm tra thông tin, lập hội đồng chấm điểm, nhập điểm, kết quả
                        người dùng:<br>
                        - Học viên: vào đăng kí hồ sơ, tra kết quả online<br>
                        - Nhân viên quản lý hồ sơ: mỗi nhân viên có một tài khoản được cấp, nhập mới hồ sơ, nhập các
                        thông tin của hồ sơ thông báo kết quả, xuất le báo cáo kết quả<br>
                        Mô hình: client server<br>
                        Công việc phụ trách: code giao diện trang chủ, chức năng thêm mới hồ sơ
                    </p>
                </div>
            </div>
            <div class="mb-8">
                <div class="mb-3">
                    <div class="flex items-center">
                        <div class="w-max flex">
                            <div class="w-48 bg-black text-white py-2 pl-4 font-bold">
                                Kỹ năng
                            </div>
                            <div
                                class="w-0 h-0 border-t-[20px] border-t-transparent border-b-[20px] border-b-transparent border-l-[16px] border-l-black">
                            </div>
                        </div>
                        <div class="w-full">
                            <div class="-ml-1 h-[3px] bg-black"></div>
                        </div>
                    </div>
                </div>
                <div class="flex justify-between">
                    <div>
                        <p>HTML, CSS, Javascript, Typescript</p>
                        <p>Database: Mysql </p>
                    </div>
                    <div>
                        <p>AngularJs, ReactJs, NuxtJs, Tailwind, Bootstrap</p>
                        <p>Khác: Java, Python, C#, .NET</p>
                    </div>
                </div>
            </div>
            <div class="mb-8">
                <div class="mb-3">
                    <div class="flex items-center">
                        <div class="w-max flex">
                            <div class="w-48 bg-black text-white py-2 pl-4 font-bold">
                                Dự án cá nhân
                            </div>
                            <div
                                class="w-0 h-0 border-t-[20px] border-t-transparent border-b-[20px] border-b-transparent border-l-[16px] border-l-black">
                            </div>
                        </div>
                        <div class="w-full">
                            <div class="-ml-1 h-[3px] bg-black"></div>
                        </div>
                    </div>
                </div>
                <div>
                    <div class="flex justify-between mb-3">
                        <div>
                            <p class="font-bold mb-1">Netflix clone</p>
                            <p>
                                Ngôn ngữ: HTML, CSS, Javascript <br>
                                Phụ trách: xây dựng lại giao diện trang chủ Netflix
                            </p>
                        </div>
                        <div>
                            <p>2022</p>
                        </div>
                    </div>
                    <div class="flex justify-between mb-3">
                        <div>
                            <p class="font-bold mb-1">Website bán giày</p>
                            <p>
                                Ngôn ngữ: Python, HTML, CSS<br>
                                Framework: Flask<br>
                                Database: Mysql<br>
                                Thành viên nhóm: 3<br>
                                Chức năng: Tìm kiếm, thêm sản phẩm vào giỏ hàng, cập nhật, thêm bớt sản phẩm trong giỏ hàng<br>
                                Phụ trách: Xây dựng giao diện trang chính, giỏ hàng, viết chức năng tìm kiếm, cập nhật thêm bớt sản phẩm

                            </p>
                        </div>
                        <div>
                            <p>2023</p>
                        </div>
                    </div>
                    <div class="flex justify-between">
                        <div>
                            <p class="font-bold mb-1">Netflix clone</p>
                            <p>
                                Ngôn ngữ: Java<br>
                                Database: Room database<br>
                                Thành viên nhóm: 3<br>
                                Chức năng: lấy ý tưởng từ 2 ứng dụng là Duolingo và Quizlet, xây dựng ứng dụng với 2 chức năng chính là học từ vựng
                                bằng flashcard và làm bài kiểm tra trắc nghiệm<br>
                                Phụ trách: thiết kế giao diện ứng dụng bằng figma, xây dựng giao diện và làm chức năng học từ vựng
                            </p>
                        </div>
                        <div>
                            <p>2024</p>
                        </div>
                    </div>
                </div>
            </div>
        </main>
        <footer>
            <div class="h-8 text-center">
                <p class="italic">@Junior203</p>
            </div>
        </footer>
    </div>
</template>
