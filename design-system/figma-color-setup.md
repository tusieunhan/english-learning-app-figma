# Hướng dẫn thiết lập Color System trong Figma

## 1. Tạo Color Styles

### Light Mode

1. **Primary Colors**
   ```
   Style name: light/primary/50 -> #EFF6FF
   Style name: light/primary/100 -> #DBEAFE
   Style name: light/primary/200 -> #BFDBFE
   Style name: light/primary/300 -> #93C5FD
   Style name: light/primary/400 -> #60A5FA
   Style name: light/primary/500 -> #3B82F6 (Main)
   Style name: light/primary/600 -> #2563EB
   Style name: light/primary/700 -> #1D4ED8
   Style name: light/primary/800 -> #1E40AF
   Style name: light/primary/900 -> #1E3A8A
   ```

2. **Neutral Colors**
   ```
   Style name: light/neutral/50 -> #F8FAFC (Background light)
   Style name: light/neutral/100 -> #F1F5F9 (Surface light)
   Style name: light/neutral/200 -> #E2E8F0 (Border light)
   Style name: light/neutral/300 -> #CBD5E1
   Style name: light/neutral/400 -> #94A3B8
   Style name: light/neutral/500 -> #64748B
   Style name: light/neutral/600 -> #475569
   Style name: light/neutral/700 -> #334155
   Style name: light/neutral/800 -> #1E293B
   Style name: light/neutral/900 -> #0F172A
   ```

3. **Semantic Colors**
   ```
   Style name: light/success -> #34D399
   Style name: light/warning -> #FBBF24
   Style name: light/error -> #F87171
   ```

### Dark Mode

1. **Primary Colors**
   ```
   Style name: dark/primary/50 -> #EFF6FF
   Style name: dark/primary/100 -> #DBEAFE
   Style name: dark/primary/200 -> #BFDBFE
   Style name: dark/primary/300 -> #93C5FD
   Style name: dark/primary/400 -> #60A5FA
   Style name: dark/primary/500 -> #3B82F6 (Main)
   Style name: dark/primary/600 -> #2563EB
   Style name: dark/primary/700 -> #1D4ED8
   Style name: dark/primary/800 -> #1E40AF
   Style name: dark/primary/900 -> #1E3A8A
   ```

2. **Neutral Colors**
   ```
   Style name: dark/neutral/50 -> #F8FAFC
   Style name: dark/neutral/100 -> #F1F5F9
   Style name: dark/neutral/200 -> #E2E8F0
   Style name: dark/neutral/300 -> #CBD5E1
   Style name: dark/neutral/400 -> #94A3B8
   Style name: dark/neutral/500 -> #64748B
   Style name: dark/neutral/600 -> #475569
   Style name: dark/neutral/700 -> #334155 (Background dark)
   Style name: dark/neutral/800 -> #1E293B (Surface dark)
   Style name: dark/neutral/900 -> #0F172A
   ```

3. **Semantic Colors**
   ```
   Style name: dark/success -> #34D399
   Style name: dark/warning -> #FBBF24
   Style name: dark/error -> #F87171
   ```

## 2. Tổ chức trong Figma

1. Tạo một frame mới có tên "🎨 Color System"

2. Tạo các sections:
   - Light Mode Colors
   - Dark Mode Colors
   - Semantic Colors
   - Color Usage Examples

3. Trong mỗi section:
   - Tạo các ô màu 64x64px
   - Thêm label hiển thị tên và mã màu
   - Nhóm các màu theo chức năng

4. Tạo các ví dụ sử dụng:
   - Button với các states
   - Text trên các background khác nhau
   - Border và divider
   - Card và surface examples

## 3. Kiểm tra Contrast

1. Kiểm tra contrast ratio cho:
   - Text màu primary trên background
   - Text màu secondary trên background
   - Button text trên button background
   - Icon colors trên các surface

2. Đảm bảo đạt chuẩn WCAG:
   - Large text (14px+): tối thiểu 3:1
   - Normal text: tối thiểu 4.5:1
   - UI components và icons: tối thiểu 3:1

## 4. Documentation

1. Thêm description cho mỗi color style:
   - Mục đích sử dụng
   - Các trường hợp nên và không nên dùng
   - Các màu tương đương trong dark mode

2. Tạo component examples:
   - Button system
   - Card system
   - Form elements
   - Navigation elements