patient_data <- read.csv("raw_data/patient_info.csv")
patient_data$smoker_binary <- ifelse(patient_data$smoker == "Yes", 1, 0)
patient_data$smoker_binary <- factor(patient_data$smoker_binary, levels = c(0, 1))
write.csv(patient_data, "clean_data/patient_info_clean.csv", row.names = FALSE)
