import streamlit as st

st.title("📊 حساب المعدل")

math = st.number_input("نقطة الرياضيات")
physics = st.number_input("نقطة الفيزياء")
science = st.number_input("نقطة العلوم")

if st.button("احسب المعدل"):
    avg = (math + physics + science) / 3
    st.success(f"المعدل تاعك هو: {avg}")
